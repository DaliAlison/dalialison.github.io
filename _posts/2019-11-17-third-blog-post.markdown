---
layout: post
title:  "What is robots.txt and how have you configure it for your site?"
date:   2019-11-17 23:05:39 -0600
categories: jekyll update
---
The robots.txt file is a text file that tells web robots (most often search engines) which pages on your site to crawl or not to crawl. 
I have for now configured my robots.txt to disallow all robots to crawl on my website.

{% highlight scss %} User-agent: * Disallow: / {% endhighlight %}