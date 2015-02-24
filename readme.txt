.inView() is a simple jQuery plugin to determine if an element is in the viewport.

Example:

$(document).scroll(function() {
	if ( $('#obj').inView() === false )	{
		// code for when #obj is NOT in view...
	} else if ( $('#obj').inView() === true) {
		// code for when #obj IS in view...
	}
});
