togglebutton
============

Simple utitlity to help deal with toggling actions. 

Examples

This will toggle an 'active' class on '#menu-wrapper' when '.menu-button' is clicked.


	$('#menu-wrapper').togglebutton({
		button: '.menu-button'
	});
		

Options
*	class_name: css class that gets toggled (default: 'active')
*	click_close: optional selector that will toggle the wrapper as well, useful for creating a close button or closing a menu on item click (default: null)
*	clear_classes: will clear all the classes on the wrapper on toggle (default: false)
* close_on_body_click: close wrapper when body tag is clicked (default: true)
