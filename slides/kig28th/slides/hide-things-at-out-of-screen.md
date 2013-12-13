##  감추세요.

<div class="fragment roll-in">
	<h4>뷰포트 밖의 Element들은 감추거나</h4>
	<h4>DOM 트리에서 제거하세요.</h4>
</div>

<pre class="fragment roll-in"><code>
	/* css way */
	body.ingame .ui {
		visibility: hidden;
		/* or */
		display: none;
	}

	// javascript way
	$(".outOfSight").remove();							// or
	$(".outOfSight").css( { "visibility": "hidden" } );	// or
	$(".outOfSight").css( { "display": "none" } );

</code></pre>