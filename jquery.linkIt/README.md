LinkIt jQuery Plugin
=====

**LinkIt** is a simple jQuery plugin to attach links to elements

## Version ##
0.1.0

## Usage ##
If you want to automatically generate links with a little extra jquery functionality, maybe this will help. Otherwise, maybe just use <a> tags like you'd normally do.
	
	//use jQuery to select all objects of the type 'span' 
    // then automatically link them to a target .
	$('span').linkIt({
    	text: 'my example text',
		href: '#',
		target: '_self';	//could also be set to a new tab with '_blank'
    });
	
	
Here's an HTML example using the above LinkIt js snippet:

    <p>Change <span>this text</span> to a link <p>

And this is what it would look like in the browser:

Change [this text]('#') to a link.

## Vendors ##
* jQuery - (as you do - [https://jquery.com](https://jquery.com))

## License ##
MIT License