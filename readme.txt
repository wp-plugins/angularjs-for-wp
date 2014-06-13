=== Plugin Name ===
Contributors: guavaworks
Donate link: http://www.codingofficehours.com/coh/#/teacher/23
Tags: angularjs, client side, single page application
Requires at least: 3.9
Tested up to: 3.9.1
Stable tag: 0.1.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

AngularJS for WordPress allows you to easily leverage the power of AngularJS and put it into your theme.  

== Description ==
  
AngularJS for WordPress was created to help anyone leverage the power of AngularJS and easily add it into their own theme.  
  
AngularJS is a client-side templating framework that lets you extend HTML vocabulary for your applications. It has a markup more similar to what HTML used to be. HTML its not a dynamic language
by itself, with AngularJS it is.
  
AngularJS for WordPress includes several directives (html elements) that will help you easily add in a block for a single post/page or a list. More directives will be added in.

__JSON REST API (WP-API)__ plugin required for AngularJS for WP to work.

Current Directives
-------------------

* `ng-post` - for getting a single post or page
* `ng-posts` - for getting a list of posts or pages 
* `ng-new-post` - for creating a client side form that creates new posts
  
View [docs](http://www.roysivan.com/angularjs-for-wordpress) for how to utilize the directives and their configurable attributes



== Installation ==

1. Download zipped archive of plugin
1. Log into your WordPress dashobard and add the new plugin via upload
1. ACtivate the plugin
1. Make sure you have the JSON REST API (WP-API) plugin also activated
1. View [documentation](http://www.roysivan.com/angularjs-for-wordpress) for how to utilize the directives


== Frequently Asked Questions ==

= Why use AngularJS? =

AngularJS renders your posts client-side. WordPress is built on PHP, so every page a user visits is converted to HTML on the server, then served to the client. With ANgularJS you are only getting a JSON Object (text) from the server
then renderring that to HTML using the client's machine. This will speed up your pages as well as allow for more concurrent visitors to your site as the strain on the server is reduced.

= What are directives? =

Directives are a way for AngularJS to hook into HTML. In the case of this plugin, HTML elements were created that hook into the AngularJS functionality.

= Installed the plugins, added in a directive but still get nothing =

This could be because the JSON REST API is not configured properly. A good way to test is make sure that you do not get a 404 when you go to www.yourdomain.com/wp-json/posts (you should see a JSON object), if you get a 404, try resaving your permalinks.

If you are still experiencing troubles use the support tab, or [e-mail me](http://roysivan.com/angularjs-for-wordpress/contact-developer)

== Changelog ==

= 0.1 =
* `ng-posts` and `ng-post` added
* `ng-post` with cat id support added

= 0.1.1 =
* minor updates to post directive javascript