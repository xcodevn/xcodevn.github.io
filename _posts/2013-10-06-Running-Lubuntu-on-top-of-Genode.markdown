---
layout: post
title:  "I wish I could run Lubuntu on top of Genode"
date:   2013-10-06 18:38:10
categories: Lubuntu Genode L4
---

Each time I think about [L4 micro kernel][l4], about [Genode][genode] framework, I always have a strong feeling that I have to do something to bring a new generation of OS into real life.

You might know the disadvantage of micro kernel is about performance. But in other side, [micro kernel][microkernel] has an amazing beauty of its design, major components of kernel (such as drivers, file system, network stack) run in `user-mode` and communicate via `IPC`. The consequence is the system will be more stable, scalable, and secure !

Now I'm trying run Lubuntu on top of Genode framework. Of course, this is just the first step for a general purpose OS becuase we'll have no more secure in this stage. But when other people (you) see a real thing, I believe you'll join with me (us) and doing this together.

I'll update my progress on this site. You can contact me at below email address.

[l4]: http://en.wikipedia.org/wiki/L4_microkernel_family
[genode]: http://genode.org
[microkernel]: http://en.wikipedia.org/wiki/Microkernel
