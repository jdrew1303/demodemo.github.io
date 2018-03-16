---
layout: post
title: "Little Languages With Peg: Getting Started"
categories: ["Little Languages With Peg"]
summary: "The practical side of building little languages (DSLs) using Peg.js. (Tips & Tricks)"
---

## WIP 

<!--`peg.js` is one of those tools that you take a look at every now and then and think "Yeah! I'm going to write my own language someday!". Then you put it away for another year. It's not that it's not a good tool. I just don't find a use for it day to day. Working mostly on internal tooling for enterprises, it tends to be the same old rubbish. Its all forms and charts and tables. Ocasionally though you get the opportunity to mix things up a bit. -->

<!--Filtering is one of those things that you need to add in to most table based projects at some stage. Normally it's checkboxes or radio buttons in a dropdown. What if we gave a user a little bit of control back? A little query language that they could use to ask questions of their data. When you mention query language people think SQL. Thats a bit heavy for most day to day tasks but one part of it is perfect: the `WHERE` predicate. It's expressions are simple and easy to understand even for the most non technical used. -->

<!--In this case though why use `peg.js`? Well, it really comes down to one thing: JavaScript. We can do all the work in the browser. Getting to grips with the `peg.js` syntax though is a different story. The documentation covers the grammar but doesnt say a word about the patterns, tips, tricks and real world usage of it in a day to day project.-->

<!--This isn't going to be a bible for working with `peg.js` but it will show you how to work through some common and not so common cases for a simple domain language.-->


```javascript 
var PEG     = require("pegjs")
var parser  = PEG.generate(fs.readFileSync("sample.pegjs", "utf8"))

```

<!--# Our little language-->

<!--```pegjs-->

<!--```-->