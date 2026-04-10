---
_edit_last: "1"
_jd_tweet_this: "yes"
_jd_twitter: ""
_jd_wp_twitter:
  - 'Sch3lp Blogs : Facebook App 191 API Error, the solution. http://schelp.co.uk/blog/facebook-app-191-api-error-the-solution/'
_oenology_layout: default
_wp_jd_bitly: ""
_wp_jd_clig: ""
_wp_jd_target: http://schelp.co.uk/blog/facebook-app-191-api-error-the-solution/
_wp_jd_url: http://schelp.co.uk/blog/facebook-app-191-api-error-the-solution/
_wp_jd_wp: ""
_wp_jd_yourls: ""
_wpbook_user_stream_id: "672991762_10150594772956763"
_wpbook_user_stream_time: "0"
author: admin
categories:
  - small-news
  - technology
  - webstuff
date: "2012-01-17T16:50:32+00:00"
guid: http://schelp.co.uk/blog/?p=1838
parent_post_id: null
post_id: "1838"
tags:
  - 191-api-error
  - facebook-app
  - wordpress
  - wpbook-lite-plugin
title: Facebook App 191 API Error, the solution.
url: /blog/facebook-app-191-api-error-the-solution/
wpbook_lite_fb_publish: "yes"
---

[![](/blog/wp-content/uploads/2012/01/konami-code-150x150.png)](/blog/wp-content/uploads/2012/01/konami-code.png)
Just added a new plugin to my blog.
the WordPress to Facebook plugin allows you to create an app in Facebook and import and export your blog posts and comments to Facebook for Facebook comments to your blog.
The previous idea of pulling in the blog posts as notes wasn't working as Facebook seems to have sidelined notes as a vital part of the service, much as they have with pages.
Hopefully with this in place things will communicate well but please be aware we are in a transition space with all this and it could fall apart at any point.
but it appears to be doing well so far
the only major problem came at the end of the process.
I had opened a Facebook app account, and set up the app as per the instructions.
I clicked back to WordPress installed and set up the plugin.
then it asked me to generate an access token. (By clicking the link provided)
every time I successfully got this error message.
> API Error Code: 191 API Error Description: The specified URL is not owned by the application Error Message: Invalid redirect\_uri: Given URL is not allowed by the Application configuration.
Rubbish.
I couldn't work out what i had done wrong.
as per the instructions I was bang on.
The Solution.
when I had specified this Blogs Address in Facebook APPs, I have put it in as "http://www.schelp.co.uk/blog'
After some internet searching I found the solution was remove the "www." within the Facebook App settings leaving "http://schelp.co.uk/blog/"
worked first time after that.
honestly, the simple things.
