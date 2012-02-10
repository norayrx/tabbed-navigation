tabbed-navigation
===========

tabbed-navigation is light-weight jQuery plugin for handling tabbed navigation with minimal markup.

Demo
----

http://chovy.dyndns.org/jquery/tabbed-navigation/

Usage
-----

	<head>
		<link href="jquery.tabbed.css" rel="stylesheet" type="text/css" media="screen" />
	</head>
	...
	<div class="tabbed">
		<ul class="tabs">
			<li><a href="#foo">Foo</a></li>
			<li><a href="#bar">Bar</a></li>
			<li><a href="#baz">Baz</a></li>
		</ul>
		<div class="contents">
			<div class="content" id="foo">Foo content</div>
			<div class="content" id="bar">Bar content</div>
			<div class="content" id="baz">Baz content</div>
		</div>
	</div>
	...
	<!-- include jquery first -->
	<script src="http://ajax.googleapis.com/ajax/libs/jquery/1/jquery.min.js"></script>
	<!-- include tabbed-navigation plugin after -->
	<script src="jquery.tabbed.js"></script>
	<script>
	$(function(){
		$(".tabbed").tabbed();
	});
	</script>


Requirements
------------

jQuery (tested with 1.7.1) 