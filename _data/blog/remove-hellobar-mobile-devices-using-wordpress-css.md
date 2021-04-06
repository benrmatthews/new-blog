---
title: 'How to remove HelloBar on mobile devices on WordPress using CSS'
date: '2014-09-03T04:53:47+00:00'
status: publish
permalink: /remove-hellobar-mobile-devices-using-wordpress-css
author: 'Ben Matthews'
excerpt: ''
type: post
id: 1204
category:
    - Freelance
tag: []
post_format: []
videourl:
    - ''
tmac_last_id:
    - '726529857086210049'
---
[Hello Bar](https://www.hellobar.com/ "HelloBar") is a popular WordPress plugin that inserts a highly visible notification bar at the top of your website or blog. Combined with a clear call-to-action button or sign up form, it’s a very effective way to direct people to a certain page on your site or get sign ups for your email newsletter.

The Hello Bar is visible on mobile devices as a default, which means it takes up a lot of screen space on smaller mobile phones, such as the iPhone. It would be great if there was a way to remove the bar on smaller devices, but the HelloBar plugin doesn’t make this possible from its settings page.

Here’s how you can remove the Hello Bar when people visit your site from mobiles, but keeps it visible when viewed on desktops, laptops or larger tablets devices.

**1. Go to Appearance &gt;&gt; Edit CSS**

**2. Copy and paste the following code:**

> /\* Remove hellobar on mobiles ————————————— \*/
> 
> @media only screen and (max-width: 700px) {  
> \#hellobar\_container,  
> \#hellobar\_pusher { display: none !important; }  
> }

**3. Click the save button**

That’s all there is to it!If that doesn’t work, open up your style.css file (available in Appearance &gt;&gt; Editor) and paste the same code into the bottom of the file, before the final ‘}’.

Now, when you visit your site from a mobile device (or resize your screen to emulate a responsive layout) the HelloBar should disappear.