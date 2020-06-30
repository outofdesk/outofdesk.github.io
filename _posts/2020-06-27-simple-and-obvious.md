---
layout: post
title:  About Simple and Obvious Things
date:   2020-06-27 00:00:00 -0700
categories: [work, productivity, learning]
description: "After it was all dealt with, my manager called me on my phone to have a chat. He was kind and responsible enough to reflect on it and think of ways he could have helped me. But there was one thing he mentioned which guided my thinking in the right direction."
image: ""
---

One afternoon on a weekday, I had a meeting with a few people at work to release the last piece of a project that was meant to change the way our clients interacted with the backend systems. It was a fairly simple change and was expected to be done in a few minutes. Not all people invited were strictly required in the meeting, so while a few joined, others kept an eye on their respective systems for signals and were kept abreast of the progress via Slack.

So there I was, in a room with a few people, talking to a few on a video call, and chatting with a couple more on the side.

Five minutes into the meeting, we did the change and shifted our attention to the monitoring systems to see early signs of success, or to minimize damage in the remote possibility of failure. Twenty minutes later, we still didn’t see any activity that we’d expected or hoped for.

The nature of the change was such that we’d expected it to take a short period to propagate but didn’t know how long exactly. So we didn’t sweat. We had theories about why it might be taking longer than usual. About thirty minutes later, we decided to involve somebody from the iOS team to simulate tests from the clients’ perspective to get some validation.

They took their sweet time to prepare for the test, and after about fifteen minutes, finally tested it. They saw some errors. When we dug into it, we learned that the clients had been seeing those errors all this time since I made the change — so for about fifty minutes. What was weird was that no whistles were blowing off, no pages triggered, so we doubted if the clients did see any errors at all, or had had any negative impact. In any case, we reverted the change, just to be safe. The errors, as you’d guess, went away.

---

When I first learned about the impact of the incident, I felt embarrassed and a little nervous. Not because it could have been avoided — that realization only came later — but because I instantly started questioning my abilities. I was trusted with it, and I was incapable of executing it. It was my lack of knowledge, I thought, that was the problem, and my self-doubt started to eat me up. At some point, I even went into denial and started blaming other people for it, at least in my mind, if not in reality.

After it was all dealt with, my manager called me on my phone to have a chat. He was kind and responsible enough to reflect on it and think of ways he could have helped me. But there was one thing he mentioned which guided my thinking in the right direction.

He asked me what my plan was before I started to work on it. How dare he ask me what the plan was, I thought. Was he asking if I had a plan at all? I’d obviously have had a plan.

Only I didn’t.

I went into the meeting, assuming that I knew all that had to be done, and I didn’t anticipate anything going wrong. So it wasn’t a gap in my knowledge that was the problem, but lack of thought and foresight, about the potential consequences and impact of the change on the system as a whole, both good and bad.

There were many pieces to look after and even though each of those tasks was fairly simple, every one of them was also crucial to the success, and because of their fragmented nature, it was really easy to miss one or two.

Atul Gawande, in his book [The Checklist Manifesto: How to Get Things Right](https://www.amazon.com/Checklist-Manifesto-How-Things-Right/dp/0312430000), mentions an essay from the 1970s by philosophers Samuel Gorovitz and Alasdair MacIntyre, which talks about human fallibility. One reason they talk about is “necessary fallibility”, which is when things go wrong because they’re beyond our capacity to control. These, by definition, can’t be prevented from happening.

But he identifies two other reasons for why things go wrong — /ignorance/, the gaps in our knowledge, and /ineptitude/, our failure to apply the knowledge correctly.

Ignorance, if we’re willing to learn, can be reduced over time; the more time we invest in something, the more we learn about it, the more knowledge we gain. But competence is something that doesn’t just come over time. Getting rid of ineptitude requires persistent effort and deliberate practice. In fact, there’s a case to be made that the more knowledge we possess, the more we stand a chance to blind ourselves to a holistic, systems thinking approach unless we’re constantly reevaluating ourselves.

The more I thought about it, the more I realized that my mistake had a meta nature to it. One is that despite having the necessary knowledge to execute the task at hand, I had failed to come up with a plan, a checklist of things that I should have had in place before I jumped on it. Second, and the meta part, is that I knew the importance of checklists, but had failed to put that knowledge too, into practice.

---

After this incident, I finally started taking the idea of checklists, the habit of note-taking, seriously.

In that spirit, here’s a list of things I’ve learned and tried to follow since:

#### Meetings
Take notes before, during, and after meetings. 

Before the meeting take note of the agenda, about what you intend to learn, what you want to say, what you expect to get out of the meeting.

During the meeting, take note of what people say, along with their names, if possible, keywords or jargon mentioned, to read about them later, questions asked, observations, and decisions made.

After the meeting, list the important things, organize and summarize ideas to make sense of it in the future. Put them in chronological order, relative to the notes of other meetings about a related, or similar topic.

#### Projects
Other than the shared documents of a project like planning document, design document, and so on, it’s immensely helpful to maintain your notes for things you’re working on. Like in software systems where you design different data models depending on the use-case and requirements, you can create multiple documents based on the nature of their use.

* “Quick Reference” document for things you’d frequently need while working on a project, for example, necessary links and resources, usernames and passwords, contact info of people important for the project, and so on.
* “Questions” document for things you need clarifications on.
* “Details” document for technical details of the project
* “Planning” document for milestones and timelines associated with the project
* “Checklist” for the list of things you’re working on, will work on and have already completed

I usually tag them by their project name, and their type, so they’re all searchable with one keyword.

#### Releases
This usually breaks out from one of the “Planning” items in the project documents. One document each for every release, with the list of things to take care of before and after the release.

#### Audience
Remember that all of these are for your benefit and sanity. Don’t get too worked up about the format or the industry conventions. If it works for you, it’s good enough. It doesn’t even have to be full sentences or grammatically correct, as long as the information contained is accurate. Pictures, links, references, anything is game. When it’s time to share or present the information to people, you can clean it up, organize, and proof-read it.

#### Progress
While stand-up, stand-down and check-in meetings are great to let other people know what you’re working on, or blocked by, keeping them as a list will help you go through the pending things in a streamlined, efficient and timely manner. You’ll also get a sense of accomplishment to see things get off of your checklist, and a feeling of closure.

#### Connections
Fragmented bits of data put together in one place helps you keep the focus on the bigger picture, and helps you find patterns and relationships between seemingly disparate ideas.

---

While this list looks fairly simple and the things in it seem obvious, if there’s one thing I’ve learned from my experience is that things that seem simple and obvious, are not necessarily easy and not so obvious.

---

## Recommended Reading

<br/>

<blockquote>
Avoidable failures are common and persistent, not to mention demoralizing and frustrating, across many fields -- from medicine to finance, business to government. And the reason is increasingly evident: the volume and complexity of what we know has exceeded our individual ability to deliver its benefits correctly, safely, or reliably. Knowledge has both saved us and burdened us.
</blockquote>
<cite>[The Checklist Manifesto: How to Get Things Right](https://www.amazon.com/Checklist-Manifesto-How-Things-Right/dp/0312430000)</cite>

---

*@out.of.desk*