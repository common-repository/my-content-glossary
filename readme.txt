=== My Content Glossary ===
Contributors: joedolson
Donate link: http://www.joedolson.com/donate.php
Tags: glossary, custom post types, post types, dictionary, definition
Requires at least: 4.0
Tested up to: 4.6
License: GPLv2 or later
Text Domain: my-content-glossary
Stable tag: trunk

Adds custom glossary features: filters content for links to terms, etc. Companion plug-in to My Content Management.
 
== Description ==

My Content: Glossary requires its parent plug-in, <a href="http://wordpress.org/extend/plugins/my-content-management/">My Content Management</a>, which creates a suite of custom post types, each with an appropriate custom taxonomy and a set of commonly needed custom fields.

The My Content Glossary helper plug-in adds Glossary-specific tools to your My Content Management plug-in so that you can better manage that area of your custom content. 

= Shortcodes: =

`[alphabet numbers='true']`: displays list of linked first characters represented in your Glossary. (Roman alphabet only, including numbers 0-9 by default.)

`[term id='' term='']`: displays value of term attribute linked to glossary term with ID attribute.

`[my_content type='glossary' display='full' taxonomy='mcm_category_glossary' order='menu_order']`: display the list of glossary terms with headings for each represented alphabet character.

= Automatic Features =

* Adds links throughout content (the first two occurrences on a page) for each term in your glossary.
* Adds character headings to each section of your glossary list.

== Changelog ==

= 1.3.8 =

* Add filter to modify format for glossary term links
* Add class on glossary term links
* Handle case variation on term links.
* Fix typo in readme
* Update tested to value 

= 1.3.7 =

* Update tested to
* Enable internationalization & language packs

= 1.3.6 =

* New filter: 'mcm_glossary_alphabet': pass in a custom alphabet array.
* Make nogloss meta value non-case-sensitive
* Updated readme.txt to include some useful information previously missing.

= 1.3.5 =

* Bug fix: PHP Notice if no terms defined
* Bug fix: in_array in strict mode to prevent 0 from being identified as having terms.
* Added class 'mcm-glossary' to inserted definition links
* Shortcode attribute: [alphabet inactive='false'] to remove letters with no related terms.
* Updated copyright, requires and tested to values

= 1.3.4 =

* Bug fix: post used to be an object in filter, is now an array; updated code.

= 1.3.3 =

* Initial release. See the <a href="http://wordpress.org/extend/plugins/my-content-management/changelog/">My Content Management changelog</a> from 1.3.2 and earlier to see previous changes.

== Installation ==

1. Upload the `my-content-glossary` folder to your `/wp-content/plugins/` directory
2. Activate the plugin using the `Plugins` menu in WordPress

The plug-in will automatically be active for any Glossary terms you have already created using My Content Management. 

== Frequently Asked Questions ==

= I installed this and it does *nothing*. What's up? =

This plug-in requires <a href="http://wordpress.org/extend/plugins/my-content-management/">My Content Management</a> to work. It's not a stand-alone plug-in. 

= I don't really get how to use My Content Management. =

There are many, many different ways to use it. I'd recommend buying the [User's Guide](http://www.joedolson.com/articles/my-content-management/guide/), which will walk you through many of the ways you can use this plug-in. Also, your purchase will help support me! Bonus!

== Screenshots ==

== Upgrade Notice ==

 * 1.0.0 Initial release as an independent plug-in.