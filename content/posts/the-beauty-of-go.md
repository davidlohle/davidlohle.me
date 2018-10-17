---
title: "The Annoying Beauty of Go"
date: 2018-04-05T16:36:01-04:00
draft: true
---

Or, "How I Learned to Stop Worrying and Love `Go Fmt`"

For anyone that's worked with Golang before, you'll know that it's a very
opinionated language. There's only one way to program in Go and whatever you're
doing is _wrong_. As a newcomer to Go, it was incredibly frustrating. When my
code isn't working, the last thing I want is a compiler yelling at me for
orphaned imports. _I'm just trying to FIX THE BUG, LET ME FIX THE BUG!
Formatting and readability can come later._

But, formatting and readability doesn't come later. Things inevitably get
sidelined for more functionality because of ship dates, etc. The end result is
some bad looking code that's a nightmare to maintain. Comments? Project
search shows 0 results for `//`

Go takes a much different approach to these things. For one, the compiler will
flat out refuse to make a binary if you have unused variables, and secondly,
through the lack of support for generics and overloading, Go pushes a vision of
a more readable (if not more verbose) codebase.

It's a hard jump to make coming from other languages that describe guidelines

Java. I've spent countless hours and written immeasurable lines of Java.
And while it made sense for the time that `loadProfile` exists as three separate functions, `loadProfile(string username)`,
`loadProfile(string JSON)` and `loadProfile(string UUID)`, 

It's also incredibly modern. You can import libraries via remote URLs. 

## On Basic Code Quality
Or, `./main.go:4:2: imported and not used: "encoding/base64"`


## On Supporting Generics and Overloading

