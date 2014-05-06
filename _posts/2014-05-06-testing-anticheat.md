---
layout: post
title:  "Testing Cheat Detection"
draft: true
category: Ingress
---

Recently I have been  conducting individual tests to find the weak points of Ingress's anti-cheating mechanism. I started with some of my most advanced techniques and lowered my efforts dramatically through each test. In every single test case Niantic has failed. Here are my test cases, keep in mind the names are not real.

Test case #1 (Shy)
- 100% spoofed
- Manually controlled spoofing
- Normal attack/defend patterns around a small target location
- Interacted positively with local community to avoid reports

Test case #2 (Asshole)
- 100% spoofed
- 1/2 manually controlled, 1/2 automatically controlled spoofing
- Aggressive attack/defend patterns around a large target location
- Interacted negatively with local community to promote reports

Test case #3 (Bot)
- 100% spoofed
- Automatically controlled spoofing
- Passive patterns around very large target location
- No interaction with local community

Results:
- Shy = 3.5m AP, no reports
- Asshole = 1.4m AP, no reports
- Bot = 650k AP, no reports (Currently still in progress)