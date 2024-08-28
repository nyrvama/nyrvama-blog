---
title: Shaping of a Bare Metal
comments: false
date: 2024-12-10 20:12:00
tags:
---

## Hardware Overview

There are two schools of thought when it comes to building a homelab; you can go
with decommissioned / second-hand enterprise hardware, or use newer, less power
hungry consumer equipment.

In Egypt, where I am currently based at, finding them newer and exciting machines
like those from ServeTheHome's [TinyMiniMicro](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwiZj9TtlNaDAxWziP0HHSjEBoUQFnoECBQQAQ&url=https%3A%2F%2Fwww.servethehome.com%2Fintroducing-project-tinyminimicro-home-lab-revolution%2F&usg=AOvVaw1yr1FwmWWdNn5wK7LwByrM&opi=89978449) series is almost impossible to find
(at realistic prices). On the other hand, beefy servers from the likes of Dell and HP, especially those from the IvyBridge to Broadwell eras are commonplace. Coupled with the fact that one of my primary goals with this endeavour is to gain experience with
the tools used in the enterprise (think the likes of VMware, ELK-stack, EKS, etc..), it was obvious to me that at least a part of my homelab must include some of those bigger boxes.

Choosing to go with used enterprise hardware adds all kinds of challenges though, including noise isolation (this all lives in our home), temperature control, and power consumption. I've implemented some basic measures to minimize the impact from those factors, but they definitely need a second iteration before it's in a state I'd be comfortable enough to share them. We'll definitely dedicate an entire article for addressing those topics some time later on.

For now, however, let's introduce the two stars of the show:

1. [Dell Poweredge R720xD LFF](https://www.dell.com/support/home/en-us/product-support/product/poweredge-r720xd/docs), with:
   - 2x Intel Xeon E5-2520v2 processors (6 cores and 12 threads each)
   - 320 GiB of DDR3 ECC RAM (running at 1333 MHz)
   - 12 3.5 inch hot swappable drive bays in the front
   - 2 2.5 inch hot swappable drive bays in the back

2. [Dell Poweredge R730 SFF](https://www.dell.com/support/home/en-us/product-support/product/poweredge-r730/docs), with:
   - 2x Intel Xeon E5-2680v4 processors (14 cores and 28 threads each)
   - 64 GiB of DDR4 ECC RAM (running at 2133 MHz)
     - *Planning to upgrade this soon*
   - 8 2.5 inch hot swappable drive bays in the front

## Storage (R720xD)

## Compute (R730)

### The Chicken or the Egg

### API-less Services

### Hardware Hardware

## What to Expect

You can find me at [Github](https://github.com/dejarikra), [LinkedIn](https://www.linkedin.com/in/dejarikra/) and [Reddit](https://www.reddit.com/user/dejarikra).
