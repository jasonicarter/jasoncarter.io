---
layout: post
title: The Product Management of WordsPlus
excerpt: "The product management of WordsPlus is a look into my journey of Product Management as an indie app developer"
tags: [wordsplus, blackberry, product design]
comments: true
---

<figure>
  <a href="/images/products/wordsplus/WordsPlus_feature_image.png"><img src="/images/products/wordsplus/WordsPlus_feature_image.png"/></a>
</figure>

## Intro
I've always thought the ideal version of a software Product Manager was awesome. A combination of market research, making shit up (lol), working closely with developers, end users, internal stakeholder and then deciding on what the product will do but more importantly, deciding what it won't do. That mixture of technical smarts and business savvy is just a cool way to spend 8+ hrs of your day - coming from a guy who's never done it. 

I never thought anything I did was close to Prod Mgr type work, but digging deeper I found a lot of examples and one in particular I remember as a great experience/experiment and that is how this post, The Product Management of WordsPlus, started.

## Why
Well, it was the money. The year was 2013, Fall, and Blackberry had just introduced their 10K competition. I was freelancing at the time and my brother suggested/convinced me that I should be patriotic, help Blackberry build out their app store and make money doing it. [The premise was:](http://developer.blackberry.com/builtforblackberry/commitment/) Build a Blackberry 10 app, based on thier new BB10 SDK (cascades, qt and C++), get over 1k downloads, make over 1k in purchases or addons, do this within 12 months and they will top you off (up to) 10K...you have to actually make 1K first so you'll only get at most 9K free. Anyways, Blackberry thought their platform was so great that if you made 1K in a year, they were damn sure you'd be able to make 10K. 

**Spoiler Alert**: WordsPlus had over 10K downloads, 450 user reviews, 4.5 avg star rating and under 1K in-app purchases.


## The Idea
The idea. How did I come up with the idea of WordsPlus? Honestly, I wanted something I liked playing (never thought of doing a utility app, had to be a game), a genre that didn't have tons of competition and something relatively easy to develop (I can code but I'm not a *ninja*, *guru* or any other *stupid name* that implies you go to weekend hackatons, drink Redbull and still appreciates COBOL).

So without any crazy market research (see below), I decided on the word game category and because I'm a terrible speler (see what I did there?), I picked the sub category of word search to avoid things like scrabble or tetris type word games where spelling was required.


## Research
Once I've decided to jump into the contest and I figured out what exactly I was going to build, the next step was to do some "market research". I know this is a little backwards - market research comes before deciding to build a new product, but bare with me. My research comprised of a few things: 

1. Download and play as many word search games as possible (I choose iOS platform for this)
2. For the top word search games in the top 100 list figure out what they all have in common
3. Ask the end users, aka friends and family, what they would like in a word search game
4. Read the reviews of these games, especially the bad reviews
5. Figure out my own personal design stlye

My research provided some great results. For example, I discovered that the word search category is not saturated with apps, particularly when compared against a genre such as arcade 2D side scroller. There were some basic features that I could consider to be required and others that were just nice to have when comparing the top apps together. And also, there seemed to be either a strong loyalty or just a lack of options in this category, I came to this determination because some apps haven't been updated for years and yet the app was still in the top 100 and receiving good reviews OR ofcourse this could be a "if it ain't broke" scenario.

As for figuring out my own personal design, I truly hated the flashy, lots of moving parts type of games (in this genre) and leaned more towards the minimal designs but still wanted some colorful splashes. I went with this as a starting point knowing the design, look and feel, and functionality will change and evolve as the product grows.


## Design

<figure class="third">  
  <a href="/images/products/wordsplus/WordsPlus_draft_2.jpg"><img src="/images/products/wordsplus/WordsPlus_draft_2.jpg"/></a>
  <a href="/images/products/wordsplus/WordsPlus_v1a.png"><img src="/images/products/wordsplus/WordsPlus_v1a.png"/></a>
  <a href="/images/products/wordsplus/WordsPlus_v2a.png"><img src="/images/products/wordsplus/WordsPlus_v2a.png"/></a>
</figure>

The look and feel of WordsPlus changed somewhat drastically across it's lifetime, as you can see below. This is mostly due to two things, features and personal taste. 

**Features:** With new features and functionality being added, the design required some restructuring. For example, when I introduced the "Word of The Day" feature I need to shift around items on the home page. And when the [Q10](http://us.blackberry.com/smartphones/blackberry-q10/overview.html) was released (with square dimensions and a physical keyboard) I wanted the app to be *visually consistent* so I updated the layout for both platforms.

**Personal Taste:** My original design was black with blue titles which I thought at the time was so sweet, needed some touchups but for a beta (more like an alpha and MVP), it was great. Remember, this was also devs only since WordsPlus was a Z10 launch title. However, as time went on I wanted a "cleaner" and more colorful look. But even with my inital switch you can see I had a few more tweaks, not just to the color but layout and logo designs as well. I even created some addition themes as in-app purchases.

<figure class="third">  
  <a href="/images/products/wordsplus/WordsPlus_v3a.png"><img src="/images/products/wordsplus/WordsPlus_v3a.png"/></a>
  <a href="/images/products/wordsplus/WordsPlus_v3b.png"><img src="/images/products/wordsplus/WordsPlus_v3b.png"/></a>
  <a href="/images/products/wordsplus/WordsPlus_v6.5c.png"><img src="/images/products/wordsplus/WordsPlus_v6.5c.png"/></a>
</figure>

## Test + Launch
For testing I really didn't do that much, or as much as I probably should have but I went with the "minimal viable product", "move fast and break things" and "fail fast, fail often" mantra. All because I wanted the first-mover advantage, remember this was for Blackberry's new platform and WordsPlus was planned as a launch title. So I pushed out my MVP and just iterated over it with improvements and bug fixing, which mostly happened in alpha/beta with only devs prior to the launch. After launch this process continued.

Going into launch I had a much more refined version of the app but one thing I sorely lacked was marketing, which honestly, I thought Blackberry was going to go "all-in" for their developers, they didn't. 

Within the first few months I had setup in-app ads and purchases. There are tons of articles on paid vs free vs freemium, so I wont go into it here but basically I started off with paid, then went to a freemium model and later removed the ads because they just weren't working and I felt it ruined the UI/UX without any good monetary return.

In the iPhone app store, I've read your launch makes or breaks the app. My experience with Blackberry was the complete opposite, as I added more value aka features/bug fixes/etc the more great reviews and downloads that came in. 

## Analyze
One of the best things I did with WordsPlus was to integrate an anlytics platform from the very beginning. I wanted to know, **who** downloaded my app, **where** the user came from, **when** they played and for how long and **what** did they were doing while playing. All of this was answered for me and more with link: count.ly

Countly is an open source, real-time, mobile analytics platform. You can either download and setup your own server or use their (free at the time, not sure about now) starter account. I have an old guest post entitled [Counting on Countly](http://www.thegadgetmasters.com/2013/05/27/counting-on-countly-for-blackberry-10/) that you can read up on but basically, it's the best thing since slice bread.

Let me give you some *interesting* stats:

- Over 10K downloads
- Under 1K in-app purchases (99cents to upgrade)
- Average of 9.2 mins per user per session
- Facebook Like and Twitter engagement were 3 times more than BBM Share or Invite to Download
- Canada, US and Nigeria were the top 3 countries

## Rinse + Repeat
Iterative. Agile. Monitor and Maintain. Whatever you want to call it, this is what I did next utilizing my roadmap, user feedback and analytics. This is probably also one of the most fun and agonizing parts of the product management process. You get to see how people actually use your app, if they like it, what they don't like about it and how to improve. I won't go into details but this is where most of my ideas for features and enhancements came from - staring at the numbers.

## Put it to Bed
Blackberry has moved on and so should I. After just over a year since the Z10 was released Blackberry continued to waiver and since then, it's shown that it no longer cares to have it's own quality consumer apps. Blackberry is now neck deep in Enterprise, as it should be, but also recently it has done two things that ready made me call it quits 

1. Allowing Amazon Android store into the mix - this just solidifies my assumptions that it has no intention to keep pushing for its own platform games and 
2. It has shut down Scoreloop. And I don't mean integrated it into the BB10 ecosystem, I mean killed it off. 

Truth be told, Scoreloop one was the hardest for me. WordsPlus was a finalist in the **2013 Blackberry Community Developer Awards for Best Scoreloop integrated game**. Something I personally, thought was well deserved, but the point is, WordsPlus was tightly integrated with it - attached at the hip is more like it - and with the end of Scoreloop, I'd have to rebuild a large chunk of WordsPlus just to provide the same functionality (leaderboard, achievements, etc). And that wasn't worth it. 

Sad to see it go, but every product must come to its end at some point. I informed customers who were waiting on support fixes, I updated and later closed the WordsPlus Facebook page and last but not least, I open sourced the [code](http://jasoncarter.io/wordsplus-for-blackberry-10-now-on-github/).

That's it. My indie Product Manager adventure (To be Continued) 

**The Product Management of WordsPlus.**