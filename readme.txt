=== CPT Slug Remover ===
Contributors: iammonzurul
Tags: slug, remove, post type, custom post type, remove slug, cpt
Requires at least: 2.9
Tested up to: 4.8.1
Stable tag: trunk

Add rewrite rules for selected custom post type so that the urls for them are in the same way as normal posts: http://siteurl/%custom_post_type_title%/.

== Description ==

In WordPress 2.9 custom post type was introduced, that opened a new world for many WordPress developers. 
When it comes to removing the slug and not destroying the rewrite rules for other post types this plugin works great. 
This only concerns those who are using %postname% as permalink structure and want to add a custom post type so that 
the urls for them are in the same way as normal posts and pages: http://siteurl/%custom_post_type_title%/.


== Installation ==

1. Upload `cpt-slug-remover` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Visit Settings -> CPT Slug Remover to set the the custom post type name/slug

== Frequently Asked Questions ==

= Which permalink structure do I need to have for this to work? =

This only works if permalink structure is "/%postname%/

== Changelog ==

= 1.0 =
* Released
