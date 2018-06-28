=== RESTless ===
Contributors: bjornw
Tags: REST-API, REST, security
Requires at least: 4.4
Tested up to: 4.9.6
Stable tag: trunk
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

RESTless disables REST calls for non-authenticated requests. 

== Description ==

RESTless is a tiny WordPress plugin which disables access to the REST API (available in WordPress since version 4.4) for non-authenticated users.
This prevents usage of the REST API by the general public and limits access to those with login credentials. No REST for the wicked. 

== Installation ==

Install this plugin as you'd install any other WordPress plugin
e.g.

1. Upload `restless` directory to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= Does this disable the REST API? =
No, it only prevents non-authenticated usage of the REST API.

== Screenshots ==

1. Message (in this case automagically translated in Dutch) shown to non-authenticated user of the REST AP upon this request https://domain.name/wp-json/wp/v2/users 
2. Request shown to authenticated user of the REST API (example request was https://domain.name/wp-json/wp/v2/users) 

== Notes == 

Credits: 

Sword icon used in the WordPress plugin repository and found as /assets/icon*
From the series ['Sketchy'](http://www.toicon.com/series/sketchy) By [Shannon E Thomas](http://www.toicon.com/authors/1)

Thanks Shannon E Thomas and to[icon] for sharing your work!


WordPress repository banner image found in /assets/banner*: 
['Draak'](http://hdl.handle.net/10934/RM0001.COLLECT.319230)

Drawn by: [Utagawa Kuniyoshi](https://en.wikipedia.org/wiki/Utagawa_Kuniyoshi) 
Dated around 1808 - 1861
Repository: Rijksmuseum.nl

Thanks Rijksmuseum!

== Changelog ==

= 1.0 =
First release



