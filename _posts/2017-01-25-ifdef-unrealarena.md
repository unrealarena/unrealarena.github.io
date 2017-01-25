---
title: '#ifdef UNREALARENA'
description: After almost 11 months of development here we are with a new snapshot!
image: /images/campgrounds_0.5.1.jpg
---

After almost 11 months of development here we are with a new snapshot!

Once again most of the work has been done under the hood: we conducted a full
code review, we removed a massive amount of dead code, we fixed a crash that
used to happen with the `/listplayers` command and finally we updated our build
infrastructure so that now we only use compilers that have at least a
feature-complete implementation of the C++11 standard.

Furthermore, with the help of `q3diff`, an in-house developed tool, we also
checked for correctness the geometry of our map Campgrounds and polished it.

<figure>
  <img src="/images/campgrounds_0.5.1.jpg" alt="Campgrounds 0.5.1">
</figure>

Last but not least, thanks to 3 big updates the engine is now at version
v0.46.0.

Next time we are going to add Quake III physics and a new map from the UT99
pool... stay tuned!

[NOTE: since there are no menus you should take a look at the instructions on
the official [wiki](https://github.com/unrealarena/unrealarena/wiki) in order to
know how to properly run the game.]
