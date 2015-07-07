---
layout: post
title: "Erlang Meets Dependant Types"
date: 2015-07-07
categories: meetups update
---

[EdLambda](http://www.edlambda.co.uk) have organised a special event on Idris-on-the-BEAM by Sam Elliot.

![Idris Logo](/img/idris_logo.png)

##Abstract

Concurrent programming is notoriously difficult, due to needing to reason not only about the sequential progress of any algorithms, but also about how information moves between concurrent agents. What if programmers were able to reason about their concurrent programs and statically verify both sequential and concurrent guarantees about those programs’ behaviour? That would likely reduce the number of bugs and defects in concurrent systems.

Erlang’s existing type system cannot produce particularly strong guarantees, especially not with regards to concurrent systems. In this talk I will describe work to integrate a dependently-typed language (Idris) with Erlang, in order to integrate dependently-typed code with Erlang programs. This work included both a new Idris code generator, and libraries for reasoning about concurrent Erlang programs, including some OTP behaviours.

It will be at the Skycanner office on the Quartermile in Edinburgh on Tuesday 14th July at 6pm.

The event is free, but please register with [Eventbrite](https://www.eventbrite.co.uk/e/erlang-meets-dependent-types-with-sam-elliott-tickets-17472346258)