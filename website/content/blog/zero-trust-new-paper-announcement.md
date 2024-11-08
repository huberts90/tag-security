---
title:  "A reader's perspective on the latest Zero Trust White Paper"
date:   2024-11-07 12:00:00 +0000
author: Hubert Siwik
---

What comes to mind when you think of Zero Trust security? Personally, I had a distorted understanding of this concept
until now, seeing it as an approach that blindly assumed that security, once granted, was eternal or... at least valid
until the next release. It roughly presumed that access policy wouldn't be violated, the network perimeter wouldn't be
breached, and a vulnerable pod wouldn't be exploited. Up until now…

After reading the TAG Security Zero Trust white paper, my understanding of this philosophy has radically changed,
and my previous view has shifted into something closer to _Limited_ Trust. The emphasis I took away 
was on the notion of total lack of confidence, regardless of the request's source. It enforces
a "trust nothing" policy, relying on metrics that are constantly evaluated and adjusted according to the current context.
Stolen credentials of a benign user or an exploited Kubernetes instance will no longer be a foothold for significant damage,
as non-standard activity is expected to be quickly identified and neutralised.

To learn how to actually implement this, immerse yourself in the reading.