---
layout: post
title: Whatever floats your boat...
categories:
- Classical Mechanics
- DIY Science
- Fun
tags:
- arXiv
- boat
- google
status: publish
type: post
published: true
meta:
  _edit_last: '4795594'
  _sexybookmarks_shortUrl: http://goo.gl/S1uBu
  _sexybookmarks_permaHash: 29d8f7aa6282ada68db72ee15c1d99d7
  dsq_thread_id: '217372772'
---
Well now. That was a long lasting spontaneous blog hiatus...

Sorry. It's not that I've run out of ideas, it's mainly lack of time... well, since time is relative, maybe it's just that I perceive myself as having less time than I actually do. But enough excuses... let's get back to the physics.
<p style="text-align:left;"><a href="http://arxiv.org/abs/0907.3333"><img class="size-medium wp-image-428 aligncenter" title="Boat Wake Measurement" src="http://morningcoffeephysics.files.wordpress.com/2009/07/wake-measurement.jpg?w=300" alt="Boat Wake Measurement" width="300" height="204" /></a>I saw a really neat (3 page!) article on <a href="http://arxiv.org/abs/0907.3333">arXiv today called "<em>Google Earth Physics</em>"</a>. I love google, and I love physics, so naturally I had to check it out. The abstract reads,</p>

<blockquote><em>Google Earth photographs often show ships and their wakes in great detail. We discuss how the images can be used to calculate the velocity of these ships.</em></blockquote>
Did someone say, do-it-yourself-physics? I knew I had to post this. Naturally, <a href="http://physicsandphysicists.blogspot.com/2009/07/google-earth-physics.html">ZapperZ beat me to it</a>... but I'll go one step further and actually try it out.

The actual article is only three pages long and is very easy to read, so if you want more details I'll direct you straight to the source. But the main suggestion of the article is that using a very simple formula and making two measurements, you can get a rough estimate of the velocity of a boat. The formula is simply,
<p style="padding-left:30px;">boat velocity =  1.25 * Sqrt(wl)/Sin(ang)</p>
<p style="padding-left:60px;">; wl is wavelength of wake in meters,</p>
<p style="padding-left:60px;">ang is angle between wake and boat direction of motion</p>

The 1.25 comes from some dimensionful constants in front involving Pi and g, but if you use standard units (meters) for the wavelength of the wake, those factors just become 1.25. (The fine print also says this assumes the boat is in deep water. In shallow water this equation isn't accurate.) You can check out the article for the real formula. To make the measurements you just need to measure an angle and the wavelength shown in the picture up at the top. You can use a protractor for the angle and a ruler for the wavelength and then use the scale given in google maps to convert between your "image length" and the actual length.

I found a <a href="http://maps.google.com/maps?f=q&amp;source=s_q&amp;hl=en&amp;geocode=&amp;q=toronto&amp;sll=37.0625,-95.677068&amp;sspn=33.626896,56.337891&amp;ie=UTF8&amp;ll=43.630279,-79.38526&amp;spn=0.000469,0.00086&amp;t=h&amp;z=20">boat in my area (toronto) on google maps here</a>. Then I used <a href="http://www.gimp.org/">gimp</a> to measure the wavelength and angle of the wake. I then converted my image length to a real length by measuring the image length of the google scale and a simple ratio:
<p style="padding-left:30px;">real distance = wavelength * real length of gscale/img length of gscale</p>
<p style="padding-left:60px;">= 76px *  10m / 93px</p>
<p style="padding-left:60px;">= <strong>8.17m</strong></p>

And  I measured an angle of around 35 degrees. Plugging that into the equation I get:
<p style="padding-left:30px;">boat velocity =  6.23 m/s = <strong>22.4 km/h</strong></p>

I'd say that's a fair velocity for a boat... but what do I know about boats. Try it for yourself and see if you get the same answer!<strong> </strong>
