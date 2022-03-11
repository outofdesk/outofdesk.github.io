---
layout: post
title:  About Simple and Obvious Things
date:   2020-06-27 00:00:00 -0700
categories: [musings]
description: ""
image: ""
---

One afternoon at work I had a meeting to release the last piece of a project that was meant to change the way our clients interacted with the backend systems. It was a fairly simple routing change at the load balancer and was expected to be done in a few minutes. Not all people invited were strictly required in the meeting, so while a few joined, others kept an eye on their respective systems for any potential misbehaviours and followed a Slack channel for constant updates.

So there I was, talking with a few people on the video call, and texting a couple more on the side.

Five minutes into the meeting, we did the change and shifted our attention to the monitoring systems to see early signs of success, or to minimize damage in the remote possibility of a failure. Twenty minutes later, we still didn’t see any activity that we’d expected or hoped for.

The nature of the change was such that it was expected to take a short period to propagate but we didn't know, or could tell, how long exactly. So we didn’t sweat. We had theories about why it might be taking longer than usual. About thirty minutes later, we decided to involve somebody from the iOS team to simulate tests from the clients’ perspective to get some validation.

They took their sweet time to prepare their devices and simulators for the test. After about fifteen minutes, we finally tested it and saw some errors. When we dug into it, we learned that our customers had been seeing those errors in Production all this time since I made the change about fifty minutes ago! What was weird was that no whistles and bells went off, no pages were triggered, so, for a moment, we doubted if the customers did, in fact, have any negative impact. In any case, we reverted the change, just to be safe. The errors, as you’d guess, went away.

---

When I first learned about the impact of the incident, I felt embarrassed and a little nervous. For how business-critical this was, fifty minutes was enternity! We should have known long before that. But the guilt and embarrasment was not because it could have been avoided — that realization only came later — but because I instantly started questioning my abilities. I was trusted with it, and I was incapable of executing it. It was my lack of knowledge and technical skill, I thought, that was the problem, and my self-doubt started to eat me up. To calm down the inner voice, I even went into denial and started blaming other people for it, at least in my mind, if not in reality.

After it was all dealt with, my manager called me on my phone to have a chat. He was kind and responsible enough to reflect on it and think of ways he could have helped me. But there was one thing he mentioned which guided my thinking in the right direction.

He asked me what my plan was before I got into the meeting. How dare he ask me what the plan was, I thought. Was he hinting that I didn't or doubting if I had a plan at all? I obviously had a plan.

Only I didn’t.

I went into the meeting assuming that I knew all that had to be done, and I didn’t anticipate anything going wrong. Saying that I didn't anticipate is an understatement. I was so confident that nothing would go wrong that I didn't consider any options for when it did go wrong. It wasn’t a gap in my knowledge that was the problem, but lack of thought and foresight, about the potential consequences and impact of the change on the system as a whole, both good and bad.

There were many pieces to this change and even though each one of those was fairly simple, they had to be executed in a specific order, and more importantly every one of those was cruicial to the success. And because of their fragmented nature, it was really easy to miss a couple of steps and roll down the metaphorical stairs.

Atul Gawande, in his book [The Checklist Manifesto: How to Get Things Right](https://www.amazon.com/Checklist-Manifesto-How-Things-Right/dp/0312430000), mentions an essay from the 1970s by philosophers Samuel Gorovitz and Alasdair MacIntyre, which talks about human fallibility. One reason they talk about for why things go wrong is “necessary fallibility”, which is when they’re beyond our capacity to control. These, by definition, can’t be prevented from happening.

But he identifies two other reasons — *ignorance*, the gaps in our knowledge, and *ineptitude*, our failure to apply the knowledge correctly.

Ignorance, if we’re willing to learn, can be reduced over time; the more time we put into something, the more we learn about it, the more knowledge we gain. But competence is something that doesn’t build over time. Getting rid of ineptitude, in other words, building competence, requires discipline, patience, and deliberate practice. In fact, there’s a case to be made that the more knowledge we possess, the more likely it is to blind ourselves to a holistic, systems thinking approach unless we’re constantly reevaluating ourselves.

Despite having the necessary knowledge to execute the task at hand, I had failed to come up with a plan, a checklist of things that I should have had in place before I jumped on it. But my mistake had a meta nature to it. I knew the importance of checklists, but had failed to put that knowledge too, which made me aware of the difference between theory and practice.

---

After the incident, I finally started taking the idea of checklists, the habit of note-taking, seriously. I especially note things that seem simple and obvious, because those are the ones that are likely to be missed, by everybody. If there’s one thing I’ve learned from my experience is that things that seem simple and obvious, are not necessarily easy and not so obvious.

---

## Recommended Reading

<br/>

<blockquote>
Avoidable failures are common and persistent, not to mention demoralizing and frustrating, across many fields -- from medicine to finance, business to government. And the reason is increasingly evident: the volume and complexity of what we know has exceeded our individual ability to deliver its benefits correctly, safely, or reliably. Knowledge has both saved us and burdened us.
</blockquote>
<cite>[The Checklist Manifesto: How to Get Things Right](https://www.amazon.com/Checklist-Manifesto-How-Things-Right/dp/0312430000)</cite>

---

*@out.of.desk*