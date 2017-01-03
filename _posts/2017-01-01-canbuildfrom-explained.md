---
title: "CanBuildFrom Explained"
categories:
  - Code
tags:
  - Scala
---

Here I am going to explain the concept of CanBuildFrom in Scala. You can surely find alot of other blogs that do the same but here I will attempt to decode the concept in plain english. So lets get started.

This said, CanBuildFrom itself is a pretty simple thing conceptually: if you have an instance of CanBuildFrom for a given collection type, you can call apply on it to get a Builder for that collection. Once you have the builder, you just add elements to it, and finally obtain the resulting collection. The trait itself is parametrized, to specify a source collection type, an element type, and a resulting collection type: CanBuildFrom[-From, -Elem, +To].
REF: http://blog.bruchez.name/2012/08/getting-to-know-canbuildfrom-without-phd.html


