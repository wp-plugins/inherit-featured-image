=== Inherit Featured Image ===
Plugin Name: Inherit Featured Image
Plugin Slug: inherit-featured-image
Contributors: jsmoriss
Tags: inherit, parent, featured, image
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl.txt
Requires At Least: 3.0
Tested Up To: 4.3
Stable Tag: 1.0

WordPress plugin to inherit the featured image of the Post / Page parent, grand-parent, etc.

== Description ==

*If no featured image has been defined* for a post / page / custom post type, then the plugin assigns a featured image from the parent, grand-parent, etc. To override the inherited featured image, simply use the 'Add Media' button and its 'Set Featured Image' feature.

The plugin hooks into the 'get_post_metadata' WordPress filter, so featured images are assigned dynamically -- disable the plugin to remove the dynamically assigned featured images. The plugin also uses the WordPress `wp_cache_get()` and `update_meta_cache()` functions to integrate fully with core WordPress functionality.

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
1. Upload the entire `inherit-featured-image/` folder to the `wp-content/plugins/` directory
1. Activate the plugin through the Plugins menu in WordPress

== Frequently Asked Questions ==

== Changelog ==

= Version 1.0 =

* Initial release.

