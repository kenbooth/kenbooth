---
title: 'WordCamp to go: Improving site performance'
date: 2010-09-24 00:00:00 -05:00
layout: post
---

![](/assets/images/wordcamp-in-a-box.jpg)While things are fresh in my mind, and because I told a few people I would, I have jotted down some notes I took away from [WordCamp Birmingham](http://wordcampbirmingham.org/) last weekend. I had intended to make one post, but after getting into it I saw it would be more useful if broken up into several posts. First I’d like to congratulate the organizers on a first-rate event and point out the event was worth many times the $40 it cost me to attend.These notes are simply things that were new or important to me and do not begin to cover all of the information offered. I’d recommend watching the SlideShare presentations for more details. Today I’ve including my notes for **improving site performance**. I’ll follow up with posts on web typography, marketing for bloggers and finally a collection of useful links I jotted down.

#### **Improving Site Performance**

If you are interested in optimizing your site, I’d recommend going through Syed Balhki’s [SlideShare presentation](http://www.slideshare.net/wpbeginner/speedupwordpresspdf). There is a lot of great advice in there and it applies to any CMS. I plan on putting a lot of it to use on one of my Drupal sites.

Some notes:

- [W3 Total Cache](http://wordpress.org/extend/plugins/w3-total-cache/) is the preferred site optimizer for WordPress. I’ve used cache software on other platforms, but haven’t used this. It seems to do it all and I’ve already turned it on for this blog.
    - Default settings are good for basic blogs and should be used on blogs of all sizes
    - It handles all types of site caching for you
    - Takes care of distributed hosting services, such as [Amazon S3](http://aws.amazon.com/s3/) and [MaxCDN](http://www.maxcdn.com/).
- Although I use PhotoShop to optimize images for the web, Sayed recommend using Smush.it as an alternative. It looks as if [Smush.it](http://developer.yahoo.com/yslow/smushit/) has been wrapped up into Yahoo’s YSlow service, but you can follow the link to get everything you need. There is also a [web-hosted version of Smush.it](http://www.smushit.com/ysmush.it/) that does not require an install.
- Optimize and repair database at least monthly. This is something I’ve not been in the habit of doing and the links below will help make it easier.
    - The [WP-DBManager](http://wordpress.org/extend/plugins/wp-dbmanager/) plugin lets optimize, repair, backup and restore your WordPress database, among many other features.
    - The [Clean Options](http://wordpress.org/extend/plugins/clean-options/) plugin finds orphaned options and allows you to remove them.
- Watch Syed’s [SlideShare](http://www.slideshare.net/wpbeginner/speedupwordpresspdf) for instructions on disabling, modifying or removing old post revisions in order to speed up performance. If you have a lot of posts on your site this is worth the effort as it clogs up your database and hurts performance.
- You can check your own site performance at the following sites:
    - [http://developer.yahoo.com/yslow](http://developer.yahoo.com/yslow)
    - [http://tools.pingdom.com](http://tools.pingdom.com/)
    - [http://whichloadsfaster.com](http://whichloadsfaster.com/)

Syed’s [wpbeginner](http://wpbeginner.com/) looks like it’s worth visiting, as well, for information on all-things WordPress.
