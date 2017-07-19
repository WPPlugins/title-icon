=== Title Icon ===
Contributors: flocsy
Donate link: http://blog.fleischer.hu/wordpress/title-icon/
Tags: plugin, title, icon, icons, image, images, pic, picture, pictures, smiley, smileys, smilies, title-icon, title_icon
Requires at least: 2.0.2
Tested up to: 2.8.4
Stable tag: trunk

Title Icon plugin displays a small icon or smiley in the title.

== Description ==

Title Icon plugin

Displays a small icon or smiley in the title. You have to add `<?php if (function_exists('the_title_icon')) the_title_icon(); ?>` to your index.php, single.php, page.php, archive.php
before or after the `<?php the_title(); ?>`

Title Icon plugin works together with:

* LMB^Box Smileys plugin (http://aboutme.lmbbox.com/lmbbox-plugins/lmbbox-smileys/)
* Smilies Themer plugin (http://rick.jinlabs.com/code/smilies-themer/)

== Installation ==

1. Upload `title-icon.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Optionally add `add_filter('title_icon', 'my_title_icon_filter');` to your code
4. When editing a post, add `title_icon` Custom Field

== Frequently Asked Questions ==

= What should I add to the 'title_icon' Custom Field? =

Use the BBCode format: `[img]the_url_of_the_icon[/img]`
For example: `[img]http://wordpress.org/favicon.ico[/img]`

= How do I use it with LMB^Box Smileys? =

Add the smiley's code to the Custom Field.
For example: `:smile_wp:`

== Screenshots ==

1. An example of how the title and the icon will look like
