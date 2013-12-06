---
layout: post
title: "Functional Programming -1"
date: 2013-12-06 21:59
comments: true
categories: 
---

Today I spent some time watching an hour-long [video](http://www.youtube.com/watch?v=ZhuHCtR3xq8&feature=share) about _Functional Programming_.

It made two significant points that struck me:

- types are just mathematical sets
- functions can be thought just like mathematical functions mapping set A to set B ( input type and return type )

When thinking like this, I all of sudden get a hint of what a _type system_ actually
might be like. Although this talk is primarily to layout the work for *monads*, it
really helps understanding programming from a different perspective than imperative.

It's about one input and one output, but multiple input can be tricked to use _currying_
to simulate ( or compose ). That has a lot of potential in reasoning about programs.

Other aspects regarding philosophy also are quite remarkable:

- The word *simple* is ambiguous. It can be "more explict, more obvious" by some, but
"more implict, more abstract" by others. The word *small* however, always implies _simple_ but without
the controversy.
- *Composability* is _the_ way to manage complexcity, or build one. This makes sense.
Random stiched up things are scary and unmaintable. In his words, we spent to much time not
productive, but just stiching tings up.