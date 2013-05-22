# Embark 

A flexible theme for your invite, early access, or preview pages.

## Quick Start

* **To change the content** (ex: "your brand name"): open the "index.html" file and edit the following line
		
		<a href="#" class="brand">Embark</a>

* **To change the styling to a sub-theme** (ex: "Tan"): open the "index.html" file and replace 
		
		<link rel="stylesheet" href="stylesheets/styles.css" type="text/css" media="screen">
with 

		<link rel="stylesheet" href="stylesheets/sub-theme-tan.css" type="text/css" media="screen">

* **To remove demonstration code**: Delete code in between the following comment in the "index.html" file

			<!-- (For Demo Purposes) -->

* **To change icons**: Embark uses [Foundation Icon Fonts 2 - General Set](http://www.zurb.com/playground/foundation-icons). For example, to change icons open the "index.html" file and simply replace 

		<i class="foundicon-edit"></i>

	with

		<i class="foundicon-photo"></i>

	or any other icon found in the "General Set".


## Making style changes with CSS

* If you are using the **default theme**: Open the "styles.css" file and then make edits according to your needs. 

		stylesheets/styles.css

* If you are using a **sub-theme**: Make sure that you've updated "index.html" to link to your sub-theme's stylesheet first (see above) and then edit your sub-theme. 

		stylesheets/sub-theme-tan.css

* Tip: I would recommend using [**Firefox's Firebug add-on**](https://getfirebug.com/) (open Firefox, right click an element on the page that you would like to change, click "Inspect Element with Firebug", make live CSS edits in the Firebug window, and when you're satisfied update your stylesheet to reflect those changes).

## Making style changes with SASS

* Make sure that you have [**Compass**](http://compass-style.org/install/) and [**SASS**](http://sass-lang.com/) configured

* Example - **How to change the "brand" color**: 

	Run 

		compass watch

	Next open the "_nav.scss" file at

		sass/modules/_nav.scss

	Then edit the default variable 

		$brand_color: #f4f4f4;

	Last, check to make sure you're changes are reflected in your browser.


