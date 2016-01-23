---
layout: post
title: Setting Up Sparx System's Enterprise Architect 12.x on Mac
---

[Sparx System's Enterprise Architect](https://de.wikipedia.org/wiki/Enterprise_Architect)
is a well known CASE-Tool. Pittily there is no native version for the
Mac. But luckily you can run Enterprise Architect on Mac via [Wine]

Using [CrossOver](https://www.codeweavers.com/products/crossover-mac2)
is even a way recommended by Sparx Systems (read instructions at
[Sparx Systems](http://www.sparxsystems.com/support/faq/enterprise-architect-WINE.html#crossover)).

This sounds pretty nice but on my MacBook Pro the installation does
not work out as expected. Everything looks fine at the first glimpse.
When you start EA it opens as expected but if you try to open
the example project it fails with an error message, saying it can't
find the DAO library.