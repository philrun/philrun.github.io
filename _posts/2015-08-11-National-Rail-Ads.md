---
layout: post
category : a
tagline: we've passed it on
tags : [Railway, National Rail, Customer Service]
comments: true
summary: National Rail's sites have been serving up all sorts of ads, even saucy ones
---

{% include JB/setup %}

##When websites go wrong, and National Rail do nothing:

<iframe src="https://vine.co/v/edXpIvKb9Id/embed/simple" width="600" height="600" frameborder="0"></iframe><script src="https://platform.vine.co/static/scripts/embed.js"></script>

<iframe src="https://vine.co/v/edDOXAZrhtY/embed/simple" width="600" height="600" frameborder="0"></iframe><script src="https://platform.vine.co/static/scripts/embed.js"></script>

##Monday 10th August

I noticed that I was being forwarded to random ad sites when looking for how my train was progressing using National Rail's live departure boards (LDB) on mobile.

As I do, I reported this to National Rail via twitter:

<img src="{{ site.url }}/images/networkrale1.png" alt="Twitter exchange #1" style="width: 300px;"/>


When I had the laptop to hand I then packet captured what was happening on the National Rail LDB site and found a bunch of redirects that could end up somewhere like this, rather than me finding out where my train was:

<img src="{{ site.url }}/images/networkrale2.png" alt="National Rail ad #1" style="width: 300px;"/>


I reported this to National Rail. They passed it onto their help desk.

##Tuesday 11th August

In the morning, the same thing happened again.

My advice to turn the ad provider off and show localised ads (e.g. the Bank Holiday works on the railway network) had fallen on deaf ears. I guess they wanted me to be 'super rich' so I'll get off the railway and stop complaining.

I passed on a few more ideas, which duly went to their help desk

##In the evening...

It happened again - earlier in the day they requested I cleared my cache (lol) so I did...but then it turned out with no cookies, the probability of having an ad that took me away from the NR LDB site increased. So...I carried on trying, and this time was told to take a cab.

<img src="{{ site.url }}/images/networkrale3.png" alt="National Rail ad #2" style="width: 300px;"/>

I think I get the message now. Phil - get off the railway

##Three stops to go...

Might as well packet capture this, so I did, and I got this ad - which I've had to cut the images from the bottom out of, because it's very explicit and really only for audiences ages 18 or over who have consented to see such material:

<img src="{{ site.url }}/images/networkrale4.png" alt="National Rail ad #3" style="width: 300px;"/>

##The packet capture

It's fairly straightforward.

Nothing malicious.

Just negligent.

Negligent from the side of National Rail/ATOC that they chose pubmatic as their ad provider, without vetting what actions they'd do. The packet capture and page source shows that pubmatic is their ad provider of choice, which occassionally bounces you off their site.

Negligent that their customers are exposed to explicit adult images. This is unacceptable, children may be using the site, and there is no 18+ disclaimer on there.

Negligent that they have done nothing to address this in the past 2 days but passing it on to their 'help desk' (those who follow my problems with Southeastern will remember how this happened before they brought Twitter inhouse).

Want to know more about pubmatic?

[Look here](http://malwarefixes.com/remove-ads-pubmatic-com-malware-removal/) - maybe National Rail should have first before picking them as an ad vendor for an all-ages site

##My advice for National Rail?

Same as it was when it started:

Remove your ad provider, put your own, NR hosted, information banners, in their place.

We pay enough as passengers than to have ads that forward us away from information we need, or show explicit imagery.

In times of delays we want to know where our trains are, not putting more money in your pockets by having us see ads from your site, or even worse being taken away from the information we want.

##Feel the same?

Share this post and lets put pressure on National Rail and ATOC to provide a better service and stop these ads on their site.

##Alternatives?

Peter Mount has a site that has data on, and isn't ad funded...

[Departureboards.mobi](http://departureboards.mobi)

##Update (Wed 12th August - 0745)

To recreate this, the best thing is to be on a new IP address that the ad provider hasn't seen - and on a mobile device.

I've heard at least 3 other reports of this happening over the last few weeks, at least one other person on an iPhone.

I guess that the ad provider is being clever, and showing the ads the first few times, and then acting 'normally' after so that it's difficult to debug. Not the kind of provider you want for an all-ages public facing website

And I'll leave you with this morning's ad, test the new iPhone, by using the old iPhone - which was shown to me by National Rail instead of details about the train I was about to board.  Dartford departures was showing the add to make me 'SUPER-RICH'. Not helpful at all

<img src="{{ site.url }}/images/networkrale6.png" alt="National Rail ad #4" style="width: 300px;"/>

##Update (Wed 12th August - 2030)

I've captured a video of a malicious ad taking me off the National Rail site - it's at the top of the page!

(animated GIF if vine doesn't work)

<img src="{{ site.url }}/images/nationalrale1.gif" alt="Malicious ad"/>
