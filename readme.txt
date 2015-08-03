=== Expire posts  ===
Contributors: sirmacik
Donate link: 
Tags: post, custom post type, expire, expirator
Requires at least: 3.0.1
Tested up to: 4.2.3
Stable tag: 1.0.1
License: MIT
License URI: http://mit-license.org/

Automatic post expirator for WordPress (with custom-post-type support)

== Description ==

## expire-post-wordpress

Automatic post expirator for WordPress (works with custom post types)

Repo was empty for some time now. Time to draw some sketchy description, since it's going to be updated soon. 

**UPDATE: first version with complete admin interface is done. Check it out in
[download section](https://github.com/sirmacik/expire-post-wordpress/releases).**

![Screenshot](https://github.com/sirmacik/expire-post-wordpress/raw/master/screenshot.png)

## Goals:
- ✓ define post-type
- ✓ define time
- ✓ expire post (move to trash or draft state) under given circumstances. 
- ✓ wp-admin interface
- make it compliant with WordPress plugins directory guidelines
- define action (this is to be written later since WordPress has really poor support of custom post statuses)=Installation ==

== Installation ==

This section describes how to install the plugin and get it working.


1. Upload `expire-post.php` to the `/wp-content/plugins/expire-post/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

== Screenshots ==


== Changelog ==

= 1.0 =
* improved time calculations
* added admin settings page
* settings kept in database instead of code

= 0.1-alpha =
* expires posts
* no other interface than code

== Upgrade Notice ==

= 1.0 =
Setup your expiration conditions once again, in dashboard section. 
