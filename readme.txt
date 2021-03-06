=== Page Builder Sandwich ===
Contributors: bfintal
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=D2MK28E7BDLHC
Tags: page builder, builder, page, visual, editor, column, columns, shortcode, layout, table, nested, composer, build, post
Requires at least: 3.9
Tested up to: 4.1.1
Stable tag: 0.4
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

The native visual editor page builder. Empower your visual editor with drag and drop & column capabilities.

== Description ==

= Call it PB Sandwich for short =

One of the most frustrating things when creating content is layouting and writing them inside the visual editor.

Sure you can use **shortcodes columns**, but are not user friendly with all those distracting square brackets. Not to mention that column shortcodes are just displayed as a single column in the visual editor.

Existing **Page builders** are also great, but we didn't want to hijack the content editor and we wanted to find a way to do it using the existing visual editor that everyone knows. Page builders have a ton of code in them for creating brand new interfaces, but more code means more stuff which can go wrong in the future.

*Check out the screenshots to see how Shortcodeless Columns works.*

= What it does =

Extends your visual editor to include page builder capabilities

= The Goal =

The goal is to create a page builder that:

* Feels and acts *native* and part of WordPress
* Leaves *most* of the content working fine event if the plugin is deactivated or deleted
* Lazy, no settings pages specific for the plugin

= What can you do with it =

* Create editable, nestable columns
* Edit text and content using the TinyMCE visual editor like how you normally would
* Live working preview of embedded content (e.g. put in a YouTube video and you can play it while still being able to drag it)
* Drag and drop TinyMCE views into other locations. Works with:
	* WordPress:
		* Image galleries
		* Videos
		* Video playlists
		* Audio
		* Audio playlists
	* Jetpack:
	  	* Video embeds *via Add Media > Insert From URL*
			* Dailymotion embed
			* Flickr videos
			* TED talks embed
			* Vimeo embed
			* Vine embed
			* Youtube embed
		* Audio embeds *via Add Media > Insert From URL*
			* Rdio embeds
			* SoundCloud embeds
			* Spotify embeds
		* Other embeds *via Add Media > Insert From URL*
			* Github Gists
	* All shortcake post elements
* Clone shortcodes/embeds & columns
* Create different shortcodes
* Working undo

= Shortcodes =

Shortcodes are added by clicking on **Add Media > Insert Post Element**.

We support the following Jetpack shortcodes. To see these, install & activate Jetpack then make sure the corresponsing feature module is activated:

* Contact Form
* *Others are still being created*

Aside from the shortcodes and embeds listed above, we've included other shortcodes as well:

* *Still being created*

*Contributions are welcome at the [Github repository](https://github.com/gambitph/Page-Builder-Sandwich/)*

= Contributing =

Report bugs and help out in the code from the [Github repository](https://github.com/gambitph/Page-Builder-Sandwich/)

== Installation ==

1. Head over to Plugins > Add New in the admin
2. Search for "PB Sandwich"
3. Install & activate the plugin
4. Create your content:
	* Click the "Columns" button while editing your posts and pages to insert your columns, or
	* Click on the "Add Media" button to insert shortcodes
5. Click, drap, drop, edit away on your visual editor

== Screenshots ==

1. Drag and drop stuff
2. You can do this while editing posts and pages
3. You then get these columns as your output

== Frequently Asked Questions ==

* [Page Builder Sandwich GitHub Repository](https://github.com/gambitph/Page-Builder-Sandwich/)
* [Issue Tracker](https://github.com/gambitph/Page-Builder-Sandwich/issues)

== Upgrade Notice ==

== Changelog ==

= 0.4 =

* Included our very first supported Jetpack shortcode: contact form
* More modular code
* Included Shortcake
* Fixed: dragging in Firefox
* Fixed: embeded video widths in Firefox
* Fixed: shortcodes with iframes drag when clicked

= 0.3 =

* Fixed bug where images were being removed inside columns
* Removed page & post type restriction

= 0.2 =

* Now uses namespaced Bootstrap classes for columns

= 0.1 =

* First release
