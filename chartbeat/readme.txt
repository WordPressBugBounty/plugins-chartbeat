=== Chartbeat ===
Contributors: chartbeat
Tags: chartbeat, analytics, amp, instant articles
Requires at least: 2.8
Tested up to: 4.7.2
Stable tag: 2.0.7

The Chartbeat plugin automatically adds real-time data and a top pages widget to your blog. See who’s on your site, what they’re doing - right now

== Description ==

Chartbeat for Publishing shows you live audience and traffic data for your websites and apps, and helps you track important trends over time. If you have a Chartbeat subscription, you can use this plugin to automatically add Chartbeat's JavaScript to your WordPress site. After installing, you’ll see your site’s traffic and audience data visualized in real time, all within WordPress. 

Questions? Problems? Need more info? Email us at [support@chartbeat.com](support@chartbeat.com).

== Installation ==

1. Upload `chartbeat.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Under Settings > Chartbeat, add your User ID
4. You may also add your API key and configure the widget (API key must have "all" permissions)
5. Select Chartbeat Publishing if you're using it
6. If you want to use the widget, drag it into your sidebar under Appearance > Widgets

To enable AMP and Facebook Instant Article analytics you just need to install the corresponding plugins. Chartbeat will be included automatically.

* <https://wordpress.org/plugins/amp/>
* <https://wordpress.org/plugins/fb-instant-articles/>


*Note that you must have your timezone set correctly for events to work properly in the historical chart.

== Frequently Asked Questions ==

= How do I sign up for Chartbeat? =

Get in touch with our team -- email us at [hello@chartbeat.com](hello@chartbeat.com) to get started. Be sure to include the name of your company, along with the website(s) you are interested to get up and running with Chartbeat.

= What does this plugin do? =

Installing this plugin will add the Chartbeat JavaScript code to your WordPress site that is required to start seeing your traffic and reader engagement in real time. Make sure you have a Chartbeat subscription before installing this plugin.

= Where do I find my Account ID? =

Your Account ID is numerical id value associated with your Chartbeat account, three to six digits in length. If you do not know your organization's account id, you can request it from your Chartbeat Account Executive, Customer Success representative, or the Technical Solutions team at [support@chartbeat.com](support@chartbeat.com).

= Will this plugin slow down my site? =

Nope. Chartbeat code is completely asynchronous, meaning it doesn't begin to run until everything else on your page has already loaded.

== Screenshots ==

1. Chartbeat Wordpress Plugin
1. Real Time Dashboard
3. Historical Dashboard

== Changelog ==

= 2.0.7 =
* Add support for engaged headline testing (http://support.chartbeat.com/edu/headlinetesting/index.html)
* Fix widget api links

= 2.0.6 =
* Fix AMP uid bug
* Add admin warning
* Add Facebook Instant Article Support

= 2.0.5 =
* Add AMP support

= 2.0.4 =
* Remove Newsbeat reference, update json encoding

= 2.0.3 =
* Fixed issue where the Chartbeat console's iframe was too short to be usable

= 2.0.2 =
* Updated handling of window load event to ensure Chartbeat is always loaded

= 2.0 =
* Added Dashboard Widget, Active Visits in Post Board and Embedded Console

= 1.4.1 =
* Fix widget error in logs *

= 1.4 =
* Security enhancements from automatic *

= 1.3 =
* 'trackadmin' option added by Jesse S. McDougall, jesse@catalystwebworks.com

= 1.2 =
* stable version

= 1.0 =
* First version. Please provide feedback.
