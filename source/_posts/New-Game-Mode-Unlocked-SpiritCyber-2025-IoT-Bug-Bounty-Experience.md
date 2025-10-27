---
title: 'New Game Mode Unlocked: SpiritCyber 2025 IoT Bug Bounty Experience'
date: 2025-10-27 16:31:58
tags:
---

I recently participated in SpiritCyber25, organised by Cybersecurity Agency of Singapore, together with YesWeHack. I am elated to share that we finished in **1st place**!

This is something I wouldn't have expected myself to try just yet, but honestly the experience was overwhelmingly positive.

## SpiritCyber25 Overview

SpiritCyber25 is a IoT hackathon that invites security researchers around the world to test, break, and report vulnerabilities in real smart devices used across Singapore, one of the most connected cities in the world. (Adapted from <https://www.yeswehack.com/page/spiritcyber25-live-iot-hackathon-in-singapore>)

This time, I participated with Elma and Jro, as Team Zammy Zamn Zamn.

## How It Went

The online qualifiers ran from 15 September to 15 October 2025, giving us a full month to enumerate the devices in scope. All these were new to me, and it felt pretty daunting... I honestly didn't know where to start.

The only prior experience I had with IoT was during my 4-month internship at HTX where I was tasked to do firmware analysis on HikVision cameras. I focused more hardware enumeration rather than software so starting SpiritCyber felt especially challenging.

Luckily, my teammates had previous SpiritCyber/Bug bounty experience and helped get the ball rolling.

Over that month, our team kept each other updated on bug-hunting progress and shared methodologies for finding issues. Those takeaways were invaluable. Although one month might sound long, juggling a heavy NUS curriculum with this competition took away a lot of the time I could have spent hunting bugs :(


> "Maybe it's the friends we made along the way."

I'm glad that I had teammates who are so willing to share their methodology on how to go about bug hunting. Even when things weren't explained in detail, observing how they worked and seeing what they shared in chat taught me a lot.

That openness also made me more comfortable making mistakes, trying new methods, and eventually finding bugs. Finding bugs is the first step, writing a PoC is another hurdle. I started by referring to my teammate's PoC, and later wrote my own PoC (with help from my bestie Claude) XD.

I worried throughout the qualifiers that my busy schedule meant I wasn't pulling my weight. When I shared this with a teammate, they offered encouragement instead of brushing my concerns aside, which meant a lot.

## Finals

Live-hacking finals felt very different from a fully online bug bounty. This year's finals was held during Singapore International Cyber Week (SICW), from 22-23 October.

I really like how the live-hacking finals was carried, where all the finalists had physical access to the devices, and that whenever we had any requests (device reset, password reset etc.), it could be handled immediately!

To add to the excitement, a new drone device was added to the existing scope, which made the competition more interesting. My team and I took afew hours trying to figure out how to take control of the drone's movements, given the files provided by YesWeHack. I guess the fun in live finals comes in when one of the organisers told us, *"If you are able to play rickroll using the drone's beeps, I will give you guys bonus points!"* 
That definitely sounded tempting so one of my teammates went to work on that while I decided to continue working on the previously-found bugs during qualifiers.

### Sharing

During the finals, I met the other 5 teams of hunters that qualified. At the end of the 2-day finals, we had a small closed-door sharing where each team presented the interesting bugs they found. It was amazing to hear the different approaches and the variety of vulnerabilities each team discovered.


## Closing

Stepping out of my usual competition comfort zone might be one of the best decisions I've made recently. I learned how to approach bug bounties, the methodologies behind bug hunting, and many different approaches to finding issues. Thanks to the sharing done by each team, I got to learn about some really interesting bugs too!

As triaging is still ongoing and the bugs have yet to be disclosed, that's all I can share for now. 

Can’t wait to share the bugs we found — I’ll post the write-ups as soon as they're ready to be disclosed!

Will I try bug bounties again? Definitely.





