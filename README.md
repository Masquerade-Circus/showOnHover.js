showOnHover.js
=================

Simple small 1 kb jQuery Plugin for create hover effects.

## Demo
http://masquerade-circus.creaken.com/Plugins/showOnHover/

##How to use:
Call the plugin on the set of elements to add the effect. 
				
##Options:
```javascript
	$(selector).showOnHover(options);
	$('elem').showOnHover({
		fx: 'fade',
		easingIn: 'swing',
		easingOut: 'swing',
		durationIn: 400,
		durationOut: 400,
		enter: function,
		complete: function,
		out: function,
		end: function
	});
```

##Effects:
't' = top, 'b' = bottom, 'l' = left, 'r' = right, 'fade', 'hide'.

You can use any valid pair of position fx, example: 't', 'tr', 'rt', 'r', 'rb', 'br', 'b', 'bl', 'lb', 'l', 'lt', 'tl'.

You can't mix 'fade' and 'hide' with position fx in the options.

##Easing:
For more advanced easing options you can use the [Easing Plugin](http://gsgd.co.uk/sandbox/jquery/easing/). 

# Legal
Author & copyright (c) 2013: [Masquerade Circus](http://masquerade-circus.creaken.com)
Dual [MIT](http://opensource.org/licenses/MIT) & [GPLv2](http://opensource.org/licenses/GPL-2.0) license
