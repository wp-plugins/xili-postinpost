=== xili Post in Post ===
Contributors: MS dev.xiligroup.com
Donate link: http://dev.xiligroup.com/
Tags: theme, post, plugin, posts, page, multilingual, widget, shortcode, template tag, conditional tag, template file
Requires at least: 3.0
Tested up to: 3.0
Stable tag: 0.9.0
License: GPLv2

xili-postinpost provides a triple tookit to insert post(s) everywhere in webpage. Template tag function, shortcode and widget are available.

== Description ==

*xili-postinpost provides a triple tookit to insert post(s) everywhere in webpage - outside or inside WP loop - . The displayed post(s) are resulting of queries like those in WP loop but not interfere with main WP loop. Widget contains conditional syntax.*

* Template tag function `xi_postinpost()` - see source , 
* shortcode like `[xilipostinpost query="p=1"]` or like `<blockquote>[xilipostinpost query="cat=3,4,150&showposts=2&lang=en_us"]</blockquote>` as in [About Page](http://dev.xiligroup.com/?page_id=3) at end.
* and widget with powerful syntax for contextual display of query's result.

are available for developers, authors and webmasters.

For each post of the resulting list, the displayed result can contain title, excerpt, content, thumbnail image with or without link to the post as single.

== Installation ==

Upload the xili-postinpost plugin to your blog, Activate it. Go to settings.
If you want to use widget, go to widget menu of Appearance menu.
To use shortcode inside post's content, refer to examples provided in these posts [here](http://dev.xiligroup.com/).
To use core function of plugin, as developer, refer directly to code source before inserting (and echoing result) the function in your theme.

= prerequisite =

* a minimum of knowledges about queries (as end part of short link) like `?p=1` or `?cat=17&tag=new`
* how are organized datas and semantic in the website.
* able to read WordPress Codex !

== Frequently Asked Questions ==

= What is  - xili-postinpost - versus  - Recent Posts - delivered by WP as default widget ? =

**Recent Posts** only displays title with link of latest posts from all categories.
With **xili-postinpost** it is possible to choose what to display and which categories or tags associated with post (and html tags or class). 

= What is *conditional* display ? =

Currently the result of widget is ever displayed. Here it is possible to use function (currents or made by webmaster) to decide when to display according context. By example if you use `is_page`, if the condition return true, the widget show the result here when a page is displayed in website. Another example with `is_category` and params `1,5,87` in the query input : when one these three categories is shown, the widget show the resulting list.

= What happens is the condition is not true ? =

If the condition is false, you can decide to show result of another query. If the condition is not inside the conditional template tags, it is possible 
to create and use a conditional function created by you (in functions.php).

= Is xili-post-in-post compatible with xili-language trilogy ? =

Yes, visit [here](http://dev.xiligroup.com/) and look on the right sidebar.

= Support Forum or contact form ? =

Effectively, prefer [forum](http://forum2.dev.xiligroup.com/) to obtain some support.

© 20101114 - MS - dev.xiligroup.com

== Screenshots ==

Run [live here](http://dev.xiligroup.com/)

1. widget setting UI for a simple query
2. widget setting UI for a simple conditional query

== Changelog ==

= 0.9.0 =
2010-11-14 - settings admin and pre-doc
= 0.8.0 =
2010-11-12 - first public release w/o settings admin

== More infos ==

* pre-tested on WP 3.0 multisite mode
* NOT TESTED ON WP 2.9.2

= Why this plugin ? =

xili-postinpost is compromise between minimum php coding (but not accessible by everybody) and end-user tool (like widget) *- but with lot of php lines in background -* to afford flexibility for webmaster and data-designer for CMS. The core function of the plugin ( `xi_postinpost()` ) and its rich argument(array with lot params) was created 3 years ago to insert by example a recent news in header, a target post inside blockquote set in content of a page or a post. Doing a public version is like finishing a book. Remind that free code is not gratis, include fees in quotation for commercial use or clients and donate. For free use, send an email!



== Upgrade Notice ==
Please read the readme.txt before.
As usually, don't forget to backup the database before major upgrade or testing no-current version found in *other versions* tabs.
Upgrading can be easily procedeed through WP admin UI or through ftp.
