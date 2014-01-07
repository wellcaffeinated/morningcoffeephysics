---
layout: post
title: Running in the Rain
categories:
- Classical Mechanics
tags:
- mythbusters
- rain
- running in the rain
- sponge bob
status: publish
type: post
published: true
meta:
  _edit_last: '1'
  _catalyst_layout: catalyst_default
  dsq_thread_id: '208082602'
  _sexybookmarks_shortUrl: http://goo.gl/4it8x
  _sexybookmarks_permaHash: dc6ceb2419af0e4a883830a49e08c4f6
---
<a href="http://commons.wikimedia.org/wiki/File:Here_comes_rain_again.jpg"><img class="alignright size-medium wp-image-668" title="Rain Drops" src="http://morningcoffeephysics.com/wp-content/uploads/2009/10/Here_comes_rain_again-300x225.jpg" alt="" width="243" height="183" /></a>So, I've never heard this myth before, but a friend asked me about it a while ago. The myth states that running in the rain will make you wetter when you arrive at your destination than if you had walked. This was on my mind recently because it was actually a bonus question in the physics lab I'm TAing for this year.

Apparently Mythbusters showed that <a href="http://en.wikipedia.org/wiki/MythBusters_(2005_season)#Who_Gets_Wetter.3F">running is a better option for staying dry</a>, but only after they corrected for a false result they'd obtained in a previous show. So how could you figure this out without going through the hassle (or fun) of running through some rain yourself?

<a href="http://www.fanpop.com/spots/spongebob-squarepants/images/154903/title/spongebob-photo"><img class="alignleft size-full wp-image-670" title="Spongebob-spongebob-squarepants" src="http://morningcoffeephysics.com/wp-content/uploads/2009/10/Spongebob-spongebob-squarepants-154903_306_315.jpg" alt="" width="122" height="126" /></a>Well, what we could do is set up an idealized situation. Imagine there are <strong>5000 drops</strong> of rain falling in every<strong> cubic meter</strong> above you. Let's say they fall at <strong>5 m/s</strong> straight downwards. To simplify things even further, let's suppose we ignore the structure of our bodies and just consider a blocky person to have a set width, depth and height. Let's make up a name for this person; Sponge Bob Square Pants (Bob for short). So, let's say Bob is <strong>0.25m thick</strong>, <strong>0.5m wide</strong>, and <strong>1m tall</strong>.

If Bob stands in the rain, all of the rain will hit his head. The number of drops hitting him per second is equal to the density of the rain times his width times his <span style="text-decoration: line-through;">height</span> <span style="color: #ff0000;">thickness</span> times the velocity of the rain in the downwards direction;

<code class="eqn">\[5000 \frac{\textrm{drops}}{m^3} \times 0.25\textrm{m} \times 0.5\textrm{m} \times 5\frac{\textrm{m}}{\textrm{s}} = 3125 \frac{\textrm{drops}}{\textrm{s}}\]</code>

If he moves (walks or runs) this amount won't change because the downward velocity of the rain won't change with respect to him. But, on the other hand, if Bob walks or runs in the rain, the rain will have a horizontal velocity with respect to him, so the rain will start to hit him in the front. We can find the number of drops hitting his front by the same method.

<code class="eqn">\[5000\frac{\textrm{drops}}{m^3}\times 0.5\textrm{m}\times 1\textrm{m} \times \textrm{V} = 2500 \frac{\textrm{drops}}{m}\times \textrm{V}\]</code>

I've just called Bob's walking/running speed <strong>V</strong>. I'll leave it like that and plug in his speed at the end. If Bob needs to run to his house which is <strong>20m</strong> away, a total number of drops of rain will hit him in front and back for the trip which we can calculate. We just need to multiply the above results by the time it takes him to get there and then add them together. That's just the distance to his house divided by his walking/running speed.

<code class="eqn">\[\textrm{time} = 20\textrm{m}/\textrm{V}\]</code>

But here something funny happens. For the rain hitting his front:

<code class="eqn">\[(2500\frac{\textrm{drops}}{m} \times \textrm{V}) \times (20\textrm{m}/\textrm{V}) = 2500 \textrm{drops}\]</code>

Hey! It doesn't depend on how fast he runs! So it really comes down to the rain hitting his head:

<code class="eqn">\[(3125 \textrm{drops}/\textrm{s}) \times (\textrm{time to get home})\dots\]</code>

The faster he runs, the less time it takes him to get home. <em>So to minimize the number of rain drops hitting his head, the faster he needs to run. </em>

<em>... but hey! I'm not the same shape as Sponge Bob, and rain doesn't always fall straight down,</em> you say?

Well, for those of you who want a more complex analysis, here's a <a href="http://www.dctech.com/physics/features/0600.php">link to an online running-in-the-rain-wetness calculator</a>. Check it out, it's fun!
