# 04-pixels

First thing I got caught with is the .push() method. I looked it up and p5.js and it is said to be a function for saving drawing style and used with pop(). But in fact, the .push() in this file is the usauge in javascript, which adds an element to the end of an array. In this case the empty array created in the first line under constructor.

I met the same problem again with .length(), frustrated at not finding reference on p5.js at first, then realize it's just a counter for elements in the array.

I think the noise() function seem to be cool. I thought it would be hard to use, but in fact it seems fairly easy. I learned that it returns value between 0 and 1.
