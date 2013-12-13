**HTML**

```
<canvas id="canvas" width="300" height="300">
</canvas>
```

**JavaScript**

```
function draw() {
	var canvas = document.getElementById("canvas");
	var ctx = canvas.getContext("2d");

	ctx.fillStyle = "rgb(200,0,0)";
	ctx.fillRect (10, 10, 50, 50);

	ctx.fillStyle = "rgba(0, 0, 200, 0.5)";
	ctx.fillRect (30, 30, 50, 50);
}
```
<br/>

* <a target="_new" href="http://developer.mozilla.org/ko/docs/HTML/Canvas">http://developer.mozilla.org/ko/docs/HTML/Canvas</a>