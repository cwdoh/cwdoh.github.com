<style>
	.view_port {
	  background-color:black;
	  height:2em;
	  width:100%;
	  overflow: hidden;
	}

	.cylon_eye {
	  color:white;
	  height: 100%;
	  width: 20%;

	  background-color: red;
	  background-image: -webkit-linear-gradient(left, rgba( 0,0,0,0.9 ) 25%, rgba( 0,0,0,0.1 ) 50%, rgba( 0,0,0,0.9 ) 75%);
	  background-image:    -moz-linear-gradient(left, rgba( 0,0,0,0.9 ) 25%, rgba( 0,0,0,0.1 ) 50%, rgba( 0,0,0,0.9 ) 75%);
	  background-image:     -ms-linear-gradient(left, rgba( 0,0,0,0.9 ) 25%, rgba( 0,0,0,0.1 ) 50%, rgba( 0,0,0,0.9 ) 75%);
	  background-image:      -o-linear-gradient(left, rgba( 0,0,0,0.9 ) 25%, rgba( 0,0,0,0.1 ) 50%, rgba( 0,0,0,0.9 ) 75%);
	  background-image:         linear-gradient(to right, rgba( 0,0,0,0.9 ) 25%, rgba( 0,0,0,0.1 ) 50%, rgba( 0,0,0,0.9 ) 75%);

	  -webkit-animation: move_eye 4s linear 0s infinite alternate;
	     -moz-animation: move_eye 4s linear 0s infinite alternate;
	       -o-animation: move_eye 4s linear 0s infinite alternate;
	          animation: move_eye 4s linear 0s infinite alternate;
	}

	@-webkit-keyframes move_eye { from { margin-left:-20%; } to { margin-left:100%; }  }
	   @-moz-keyframes move_eye { from { margin-left:-20%; } to { margin-left:100%; }  }
	     @-o-keyframes move_eye { from { margin-left:-20%; } to { margin-left:100%; }  }
	        @keyframes move_eye { from { margin-left:-20%; } to { margin-left:100%; }  }
</style>

##  애니메이션(Animation)

* #### 미리 정의한 키프레임을 이용하여 주어진 시간동안 속성을 변화
* #### 복잡한 값의 변화도 키프레임의 정의를 통해 가능

<div class="view_port">
  <div class="cylon_eye"></div>
</div>
