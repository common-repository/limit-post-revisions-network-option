=== Limit Post Revisions Network Option ===
Contributors: dsader
Donate link: http://dsader.snowotherway.org
Tags: multisite, network, revisions, post revisions, autosave,
Requires at least: 3.0
Tested up to: 4.6
Stable tag: Trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

A Multisite Network plugin to add Network Admin->Settings to limit, or disable, the number of post revisions and set the post autosave interval.

== Description ==

A [Multisite](http://codex.wordpress.org/Create_A_Network) Network plugin to add Network->Settings to limit, or disable, the number of post revisions and set the post autosave interval.


== Installation ==

This section describes how to install the plugin and get it working.

1. Upload the plugin to your blog, Network Activate it
2. Go to Network Admin->Settings to set "Post Revisions" and "Autosave Interval".

== Frequently Asked Questions ==

* Do I need this plugin if I have WP_POST_REVISIONS and AUTOSAVE_INTERVAL defined in my wp-config.php? No.
* Will this plugin delete existing post revisions? No. It defines the constant WP_POST_REVISIONS and WordPress takes care of the rest.
* Should I set the Autosave Interval to 0? No, I recommend 300, the WP default is 60.

== Screenshots ==

1.  Go to Network Admin->Settings to set "Post Revisions" and "Autosave Interval"

== Notes ==

I based the default plugin values for the constants AUTOSAVE_INTERVAL and WP_POST_REVISIONS on the discussion here: http://wpmututorials.com/how-to/managing-autosavepost-revisions/

== Changelog ==

= 4.6 =
* WP 4.6 tests OK, cleanup php notices

== Upgrade Notice ==

= 4.6 =
* WP 4.6 tests OK, cleanup php notices