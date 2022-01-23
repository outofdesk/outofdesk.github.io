---
layout: post
title:  "Book Notes: Cloud Native Patterns"
date:   2022-01-23 00:00:00 -0700
categories: [cloud, technology, cloud-native, software architecture]
description: ""
image: ""
---

As I read the book [Cloud Native Patterns, by Cornelia Davis](https://www.manning.com/books/cloud-native-patterns), I plan to use this space to document things I learn, read and think about along the way. As such, I expect this to be a constantly changing and evolving post, much like the cloud systems that the book talks about.

**Cloud-first before cloud-native** – Cloud-first is a good precursor to understanding what cloud-native means and what it has to offer. Although the way people define cloud-first strategy varies widely, it essentially is thinking of the cloud as the primary medium of running your software, as opposed to the on-premises approach that tied all your systems to a set of servers in a specific physical location that you owned or managed. Cloud is, more than anything, a layer of abstraction built to free the developers’ minds from the concerns of how to run systems and promote thinking about what to build.

**Natural Side-effects of moving to the cloud** – Think of taking care of your babies at home versus sending them to daycare. A natural and inevitable side-effect of sending your baby away for a few hours is that you lose some control. It’s neither good or bad, it just is. So while it relieves you of some duties and responsibilities, it also raises the stakes in other ways. Similarly, when you take your systems from your premises to the cloud, it means that you lose some control. But it doesn’t magically solve all your problems, it solves some, and throws other, newer problems at you.

**Inherent characteristics of the cloud** – Going back to the daycare example, it’s a more dynamic place than your home. There are other actors at play – other babies, the care-givers, other babies’ parents, and the challenges of an unfamiliar setting. In other words, it’s a chaotic place. Things are not always predictable, and are bound to go wrong, in one way or the other. Because of the sheer number of unknowns, learning about all of them, let alone preventing all the problems is not an option. Cloud is exactly like that too. There are other systems at play, their dependencies, and the shared infrastructure, needless to say all that bound by the laws of Physics. It sounds scary at first, but accepting these truths enables us to think about how to build systems that function amidst the chaos, despite all the failings.

**So why go to the cloud** – If you lose control and visibility into our systems, why on Earth would you want to migrate? Because absolute control and perfection are delusional goals to build your life or business upon. And while you lose some control on how your systems work together, you gain control on what your systems does, or how they provide value to the customers. If you had all the time in the world, you would have taken care of your babies at home. Not that you don’t like them going out, but that you would like to be around them as much as you can. But time is finite, and society and its changing needs throw a lot at you to juggle. In order to do the best with your time, you prioritize things and delegate or outsource some responsibilities. As technology has come to dominate most people’s lives, the changing needs of society often translates to changing needs of software. As the demand of your business increases, you’re compelled to not only prioritize time, but the limited material resources you possess.

**Desirable characteristics of a business** – In order to serve the ever-changing needs of the society, certain characteristics naturally emerge that are desirable to run a successful business. Simply put, a business should provide the value promised to all its customers, anywhere and anytime, and evolve quickly to address their needs.

*All its customers* – In the world of the Internet, your customers come from different backgrounds, cultures, ages, and gender, they use different devices, and operate under widely different constraints. So accessibility, multi-language and multi-device support now become first-class citizens.

*Anywhere and anytime* – When your customers are based in different geographical locations across continents, compliance to legal and other policies, and the ability to operate in different time-zones, essentially being available around the clock are of prime importance.

*Evolve quickly* – Evolving quickly to serve such a diverse group of customers and a unique set of constraints means having shorter and accurate feedback cycles.

**Cloud-native** – is an umbrella term used to capture a set of ideas, principles, processes and tools, that aims to marry the inherent characteristics of the cloud with the desirable characteristics of today’s business in a seamless manner.

## Recommended Reading
-----

[Cloud Native Patterns, by Cornelia Davis](https://www.manning.com/books/cloud-native-patterns)

[What is Cloud Native](https://docs.microsoft.com/en-us/dotnet/architecture/cloud-native/definition)

*****

If you have any comments about the post, send me a message on any of my social media profiles, or email me at *contact.outofdesk [at] gmail [dot] com*
