---
title: 'Customizing Sitecore&#8217;s Page Editor Ribbon'
layout: post
permalink: /customizing-sitecores-page-editor-ribbon/
categories: [digital marketing]
tags: [beginners, page editor, sitecore]
comments: true
---
Recently, I&#8217;ve been working with a client who requested access to the page&#8217;s meta data from the Page Editor (basically any data that wasn&#8217;t displayed to the user on the front-end but still very essential to the use and functionality of the page). Customizing Sitecore&#8217;s Page Editor ribbon to provide access to data via the Page Editor is actually quite a straight forward task once you know where everything is and you understand the Sitecore terminology for things. So lets get started&#8230;  
<!--more-->

## Why do it?

Because the customer said so. It makes sense. And it&#8217;s easy to do. Three things that rarely come together. Why miss the opportunity to get on your client&#8217;s good side???

## Location, location, location

Normally, most of my time is spent in and working with the Master database. This time in order to change the Page Editor ribbon we&#8217;ll need to go into the Core db. So switch over to the Core (if you don&#8217;t know how, check out my <a title="Switching databases on Sitecore Desktop" href="http://jsoncarter.com/switching-databases-on-sitecore-desktop/" target="_blank">previous article</a>) then go to the following path -sitecore/content/Applications/WebEdit/  
<img class="alignleft wp-image-164 size-full" src="http://jasoncarter.io/wordpress/wp-content/uploads/2014/08/webEdit.png" alt="Web Edit" width="232" height="554" />

First off, the folder is called WebEdit and not something convenient like &#8220;PageEditor&#8221; because, as the story goes, what we call the Page Editor used to be called the Web Editor (or something like that). Plus, now with Sitecore moving into branding everything with &#8220;Experience&#8221;, I&#8217;m sure it&#8217;ll be renamed in the next release.

## Terminology

Like a lot of things in Sitecore, terminology tends to be a (small) hurdle. The picture below is much better at explaining this than I am&#8230;

### Ribbon + <span style="color: #3366ff;">Strip</span> + <span style="color: #339966;">Chunk <span style="color: #000000;">+</span> <span style="color: #ff0000;">Button</span></span>

<img class="aligncenter size-full wp-image-186" src="http://jasoncarter.io/wordpress/wp-content/uploads/2014/08/page_editor_ribbon.png" alt="Page Editor Ribbon" width="714" height="102" />

## Duplicate!

The best way I found to get started on adding a custom button is duplicating an existing one.

  1. Duplicate the Page Editor item and rename it to Properties
  2. Delete all items under Page Editor except Edit (Edit has all the best examples of buttons)
  3. Most of the necessary details will already be filled out for you so you&#8217;ll just need to rename fields such as ID and Header to something like PropertyID and Properties for the Strip
  4. Do the same for the Chunk and name it something like Meta Data
  5. Under Meta Data create/change the button to Edit Meta Data and remember to change icons
  6. This step is probably the trickiest part, where you&#8217;ll have to setup the Command where it&#8217;s looking for an ID. I used the same item ID of the actual button. The fields should reflect those of the actual field names (exactly) that you want the button to update, separated by the pipe &#8216;|&#8217;`webedit:fieldeditor(command={50B4AAC4-F1BA-4D7D-4752-80C42412C5A8},fields=Description|Keywords)`

If you&#8217;ve duplicated the existing Chunk then it&#8217;s pretty easy going from there and for me, messing around with the IDs, icons, fields and tooltips to get everything just right was the biggest challenge &#8211; that and actually figuring out what the hell is a Chunk!

What custom buttons are you adding to the Page Editor and why?