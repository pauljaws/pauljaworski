---
title: "My First Post"
date: 2018-05-22T17:47:47-07:00
draft: true
---

Let's see what this looks like. Cool. But what if you didn’t actually define that constant in your new file?

Now you’re about to experience one of the most frustrating bugs possible in a Redux app — importing an undefined constant into a reducer. Your tests will break, your app will break, and you’ll bash your head into your desk until you figure it out.

The problem is that this type of bug just fails silently. ES6 imports don’t care whether or not the variable you’re importing is defined. You’ll never see an error about it.
