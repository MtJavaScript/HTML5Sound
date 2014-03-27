HTML5Sound
==========
 Very small HTML5 audio JavaScript lib
#Include
``` html
<script src="lib/html5-sound.js"></script>
```

# Samples
## Sample 1
``` html
<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/2.1.0/jquery.js"></script>
<script src="lib/html5-sound.js"></script>

<button id="sound1">Sound 1</button>
<button id="sound2">Sound 2</button>

<script>
$("#sound1").click(function(){
	var s = new Mt.Sound({
		src: '/lib/mp3/bb1.mp3'
	});
	
	s.play();
});

$("#sound2").click(function(){
	var s = new Mt.Sound({
		src: '/lib/mp3/bb2.mp3'
	});
	
	s.play();
});
</script>
```