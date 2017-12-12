---
layout: post
title: "Little Languages With Peg"
category: blog
summary: "The practical side of building little languages (DSLs) using Peg.js. (Tips & Tricks)"
---

# WIP


```javascript 
var PEG     = require("pegjs")
var parser  = PEG.generate(fs.readFileSync("sample.pegjs", "utf8"))

```