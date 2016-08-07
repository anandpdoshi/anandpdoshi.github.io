---
layout: post
title: MIT Magnifies Motion
excerpt: MIT's team find a way to monitor neonatal babies and see invisible motion using just a camera and their software
xpost: '<a href="https://frappe.io/blog/technology/mit-magnifies-motion" target="_blank">Frappé Blog</a>'
---

What’s the easiest way to catch an invisible man (or Harry Potter)? Well, just throw some paint! Though an oversimplified explanation, that’s what MIT’s scientists did, to capture things invisible to our eyes.

The initial aim of the project was to monitor babies in neonatal care without putting needles into them. A way to monitor heart rate and breathing status. And what an elegant solution they came up with!

Human skin is slightly translucent and when blood flows through it, its color changes. Such a change is imperceptible to the human eye. So, they wrote a program to increase the intensity of such color change, in a video showing a sleeping baby. The resulting video showed the baby’s face flush red at regular intervals of 151 per min, which was very close to its heart rate.
	
They were able to measure heart rate with a camera!

---

<div class="embed-responsive embed-responsive-4by3">
  <iframe class="embed-responsive-item" src="https://www.youtube-nocookie.com/embed/XNGFTpNibkw?rel=0"></iframe>
</div>

---

Meh! This is the 21st century. Something like this was expected.

Wait! There’s more to it. Eventually, the team realised that their algorithm could be used to amplify motion as well. Instead of amplifying colour, they amplified the position of the pixel between two frames of a video.

They were able to check if a baby is breathing using a camera!

---

<div class="embed-responsive embed-responsive-4by3">
  <iframe class="embed-responsive-item" src="https://www.youtube-nocookie.com/embed/nsjtUboO6BM?rel=0"></iframe>
</div>

---

So, how about lie detection, unraveling magic tricks or detecting gas leaks? Imagine it being a part of your mobile phone, google glass or the airport’s security system. This algorithm, known as **Eulerian Video Magnification**, has far reaching applications apart from medical ones.

And they have open sourced the code, for non-commercial purposes. Unfortunately it is in MATLAB, which most of us cannot afford.

But the good news is that you can head over to <a href="http://videoscope.qrclab.com/" target="_blank" data-mce-href="http://videoscope.qrclab.com/">http://videoscope.qrclab.com/</a> and try out the algorithm on your own videos. Have fun :D.

**References:**

- [http://people.csail.mit.edu/mrub/vidmag/](http://people.csail.mit.edu/mrub/vidmag/)
- [http://bits.blogs.nytimes.com/2013/02/27/scientists-uncover-invisible-motion-in-video/](http://bits.blogs.nytimes.com/2013/02/27/scientists-uncover-invisible-motion-in-video/)

---

**Here’s the official video found on their website:**

<div class="embed-responsive embed-responsive-4by3">
  <iframe class="embed-responsive-item" src="https://www.youtube-nocookie.com/embed/ONZcjs1Pjmk?rel=0"></iframe>
</div>
