140k Functions
------

**Original functions around 140k in size**

What is this?
----

Inspired by websites like http://www.140byt.es and http://microjs.com I've been striving to write small javascript libraries and functions.  I decided I would post them in a GIT repository and let any who needs use them,  I release these as is and I'll update them as I get time.


*Object Literial Count:*<br />
JavaScripts has arrays have 'length' to get the number of object in an array.  Why don't object have the same functionality?  Here is what I came up with currently clocking in as 78k:

<pre>
Object.prototype.count=function(){var b=0;for(a in this){b++}return(b-1)};
</pre>

Usage:

<pre>var x = { a:1, b:2, c:3 };
console.log( x.count() + " should be 3" );</pre>
