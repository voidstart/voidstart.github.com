---
layout: post
title: "Algorithm Design Manual - 2"
date: 2013-12-04 22:51
comments: true
categories: 
---

I thought I'd just start to warm up myself by writing some sorting
algorithm.

At first, I thought to first write some random generator for testing usage. Then
I realized that's not the goal, to compare each algo with different types of inputs.
I am just trying to implement _correct_ sorting. The performance, code compactness,
caching all are not my concerns. So the result is hardcoded _random_ input, and I
will print the whole array after each _pass_ or interation (after swap etc), to
observe the _sorting process_ and final sorted array.

I did from scatch the bubble, insertion, selection and merge sort. Turns out it's
not easy to get right the first try even for such simple algorithm. My errors mostly
on index off by 1, edge cases. Time spent mostly on thinking the _sorted_ vs the _unsorted_ part,
and their transition. Direction, index, temps are most concerned.

It's good excercise.


I review some other things besides this:

- the spiral rule of c++ declaraions
- c++ quiz quesions (includes some c++ 11 stuff)
- stack and queues

