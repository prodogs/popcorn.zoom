# Popcorn.zoom.js


Zoom and Rotate Popcorn video objects, like this...

	var $pop = Popcorn( "#video-id" );

	//	zoom to 1.5 the original size
	$pop.zoom( 1.5 );

	//	zoom to 1.5 the original size and rotate 45 degrees
	$pop.zoom( 1.5, 45 );

	//	More examples...
	
	$pop.zoom({ 
		scale: scale, 
		rotate: 0
	});
	
	$pop.rotate( 45 );
	
	$pop.rotate({ 
		rotate: 45, 
		scale: 1 
	});

Fun with zomming and rotating: (screen cap from the functional tests)
<img src="https://github.com/rwldrn/popcorn.zoom/raw/master/test/assets/screencap.png">
