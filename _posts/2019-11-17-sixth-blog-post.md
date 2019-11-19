---
layout: post
title: "What is Open Graph and how do you make use of it?"
date: 2019-11-17 23:02:30 -0600
---

The <a href="https://ogp.me">Open Graph protocol</a> enables any web page to become a rich object in a social graph. For instance, this is used on Facebook to allow any web page to have the same functionality as any other object on Facebook.<br>
In other words, it gives you control over how your website is presented when shared in social media.

To turn your web pages into graph objects, you need to add basic metadata to your page. The metadata is set in the head section of your code(like meta tags).
There are four required properties:


<ul>
  <li>
    <p>og:title - This defines the title of the content.</p>
  </li>
  <li>
    <p>og:type - Describes the type of object shared, for example a blog post, a video, an image, etc.</p>
  </li>
  <li>
    <p>og:image - An image URL which should represent your object within the graph.</p>
  </li>
  <li>
    <p>og:url - Describes how the canonical URL is set for the page shared.</p>
  </li>
</ul>

I used Open Graph to be able to control how my website is presented when I share it in social media. In the head section of the code I used Jekyll's templating language, Liquid, with help of if statements to see if for instance a page title or an image is present.