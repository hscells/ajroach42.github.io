---
layout: post
category: post
published: true
title: Blogging at 19200 baud
---

I recently acquired a Gateway Handbook 486. It's a tiny DOS laptop released in 1994. Tiny might be the wrong word. It's the largest DOS machine I own (after my HP 200LX and my Prolinear Palmbook 386), but it's Tiny compared to other laptops of the day, and especially laptops with a 486. I used it to write this post. ![header.jpg]({{site.baseurl}}/images/header.jpg) 

(That's the Handbook on the left and the LX on the right) 

I like the machine a lot. Mine has a dead battery, which is a bummer, but it works well when plugged in. All of them, basically, will have dead batteries, or nearly so, and the battery was nonstandard, and not designed to be user servicable. Thankfully, there's a big difference between Not Designed to be user servicable and Not user servicible. [Several intrepid hackers have posted instructions on how to modify these batteries to accept modern NiHM AAs](http://jeff.mulb.us/articles/gwhb/gwhb.php), which is what I plan on doing. With a good set of modern NiHM AAs, I should get ballpark 8 hours on a charge. 

Right now, I'm using the handbook as a serial terminal connected to a Raspberry Pi. In the coming weeks, I plan to get SLiRP configured on the pi, to emulate a SLIP connection, so that the handbook can connect to the modern, wireless internet directly. When I do, I'll lean on DOSLYNX and other packages from FreeDOS to keep it working. 

Until, then, though, I'm using it as a serial terminal for the Raspberry pi, which means I have git and elinks and mutt and [everything else listed under Serial Terminal in that ridiculous article I wrote.](http://ajroach42.com/a-modern-office-with-vintage-hardware/). I'm able to edit this blog from that machine from 1994, which is pretty neat, and using [Brutaldon.online](https://brutaldon.online), via Elinks, I'm even able to participate in modern social media. 

All in all, I'm enjoying using this machine. Once I have my toolchain a little less temporary, I'll post a writeup of the steps that I took to get there, and how you can do the same.
