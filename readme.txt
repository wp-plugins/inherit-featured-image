=== Inherit Featured Image ===
Contributors: jsmoriss
Tags: inherit, parent, featured, image
License: GPLv2 or later
Requires at least: 2.9
Tested up to: 3.7.1
Stable tag: 1.0

Inherit the featured image of the parent, grand-parent, etc.

== Description ==

*If no featured image has been defined* for a post / page / custom post type, then the plugin assigns a featured image from the parent, grand-parent, etc.

The plugin hooks into the 'get_post_metadata' WordPress filter, so featured images are assigned dynamically -- disable the plugin to remove the dynamically assigned featured images.

The plugin also uses the WordPress `wp_cache_get()` and `update_meta_cache()` functions to integrate fully with core WordPress functionality.

== Installation ==

*Using the WordPress Dashboard*

1. Login to your weblog
1. Go to Plugins
1. Select Add New
1. Search for *Inherit Featured Image*
1. Select Install
1. Select Install Now
1. Select Activate Plugin

*Manual*

1. Download and unzip the plugin
1. Upload the entire inherit-featured-image/ folder to the /wp-content/plugins/ directory
1. Activate the plugin through the Plugins menu in WordPress

== Frequently Asked Questions ==

== Changelog ==

= Version 1.0 =

* Initial release.

