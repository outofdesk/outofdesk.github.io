---
layout: post
title:  "Brooks' Law as a Special Case of Amdahl's Law"
date:   2022-03-29 00:00:00 -0700
categories: [management]
description: ""
image: ""
---
----
#### Brooks' Law 
----

From Wikipedia: *“Brooks' law is an observation about software project management according to which "adding manpower to a late software project makes it later"*. This was put forth by Fred Brooks in his classic book “The Mythical Man Month”, in 1975.

The reasons as explained by Brooks are three-fold, which I thik can be reduced to the following two, after merging last two of the original three together
* Any time spent in getting the newer members productive, is time stolen from the time until the deadline
* Inherent lack of divisibility – The less divisible the tasks are, the more the time spent in managing their dependencies and communication. Again, any time not directly spent in working towards the delivery is time stolen from the time until the deadline, at least in the short-term. The famous example captures the essence of this quite aptly: “While one woman can deliver a baby in nine months, nine women can’t deliver a baby in one month”. Since the “work”, in the example, is completely indivisible, the benefit of adding more manpower, or womanpower in this case, yields zero benefit.

----

#### Amdahl's Law 
----

Amdahl’s law, presented by Gene Amdahl in 1967, states that *"the overall performance improvement gained by optimizing a single part of a system is limited by the fraction of time that the improved part is actually used"*. It is often used in parallel computing to predict the improvement in performance achieved by using multiple processors. An example of this is that if a task is 10% non-parallelizable, then any benefit of adding more processors only applies for the rest of the 90% of it.

While the language used to describe them and the realms they are applied in are different, the idea is the same. In fact, Amdahl’s law is a general case of Brooks' law.

----
#### Amdahl's Law in Project Management
----

A deadline is the time at which you’re expected to be completed with the project. Let’s say the deadline is time D. If the time at which you add more resources is time T, then you'd get the most benefit out of adding more people to a project if the period they are actually contributing directly towards the release is D-T, i.e. all the rest of the time until the deadline. But since a non-trivial amount of time is lost in bringing them up to speed, your team ends up spending until, let's say, time X. Hence the fraction of time the additional resources(improved part) are actually used is limited to *D-T-X* at most, assuming no further dependencies and communication. If the project is already running behind schedule, it means that you just stole precious time, most likely leading to missing the deadline. The overall benefit is hence limited by the indivisibility of tasks in some parts of the project.

----
## Recommended Reading
<br/>

[Brooks' Law](https://en.wikipedia.org/wiki/Brooks%27s_law)

[Amdahl's Law](https://en.wikipedia.org/wiki/Amdahl%27s_law)

---

*@out.of.desk*
