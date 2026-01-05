---
layout: post
title: "Automation and induced demand"
---

When deliberating whether to automate a process, it’s natural to ask *“Do we do this often enough to make it worth automating?”*

This is a very reasonable question. After all, spending 10x the time to automate a process that’s rarely invoked is a bit of a trope for a reason. There's even [an XKCD about it](https://xkcd.com/1205/). (That said, there's an XKCD about everything!)

However, when answering this question, we must be careful not to conflate low *frequency* with low *value*. It’s very possible that the frequency is low simply *because* the task is arduous — and if we automate it, the process may be used way more often, unlocking tons of value!

It’s a bit like sizing the market for a new startup; today’s market opportunity might be small, but it’s the future opportunity that really matters.

I’ve personally made this mistake, specifically regarding how much to invest in automating the process of spinning up a new microservice. Again, it’s not unreasonable to ask “Well, how often do dev teams spin up new services, anyway?”

However, in this example, we also need to consider

1. What are teams doing instead of creating new services? I.e., what workarounds are they employing — are they adding tangential scope to existing services, making things more complex?
2. If we made it easier, would teams do it more often? What benefits would that convey?

Through this lens it's easier to see that the juice may very well be worth the squeeze.

The economics term for this is [induced demand](https://en.wikipedia.org/wiki/Induced_demand). I’m always happy when I get to link my BA with my PM experience!