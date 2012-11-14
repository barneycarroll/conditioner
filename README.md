conditioner
===========

Because it's worth it.

There comes a time when I think I'd like a `switch case` statement but with cleaner structure and a bit more logic in the cases, or where I'm writing a big rolling `if ... else if ... else` statement and I end up with loads of nesting, repetition, etc. It's often a scraggly mess with split ends, I struggle to express the logic, and I just wish the conditional stuff were more elegantly (nay, lustrously) expressed.

So my adding a bit of volume and a lot of gloss, I want to write a JS framework for structuring conditional outcomes. Think of it as a more generalised, flexible and customisable [yepnope.js](http://yepnopejs.com): you feed in some setup/settings to a `new Conditioner` and pass in your tests, outcomes etc.