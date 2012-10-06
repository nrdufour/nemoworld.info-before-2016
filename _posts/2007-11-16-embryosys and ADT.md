---
layout: post
title: Embryosys and ADT
---

Ok I have finally found the time to put on <a href="http://code.google.com/p/embryosys/" target="_blank">google code</a> the first pieces of embryo systems.

I hesitated between Google code and hosting myself the code. I opted on Google for its longevity, I guess ;)

Anyway, this first version contains only the libdss to manipulate DSS object (stands for Data System String). It will be a practical way to store the ADTs in the engine. Basically, it contains a header (with its type and id) and a set of fields (pair key/value). To be short: a very stupid simple way to store structured information. Perhaps I will change that to use xml instead... who knows.

Those DSSs will provide a good base and the next step is libadt which will provide everything you need to create ADTs. What we’ll be missing too is the persistent manager that will come as well. I haven’t decided yet on the backend type (database, filesystem,...).

To be continued...

<blockquote><strong>Update</strong> (2008/08/29): I have abandonned that hosting simply because I don't like the fact I can't really control the infrastructure or make it better / add feature. Now everything is back on my own server using Trac (<a href="http://nemoworld.info/projects/embryo">http://nemoworld.info/projects/embryo</a>).</blockquote>

<blockquote><strong>Update</strong> (2011/04/11): Any Embryosys news should be found here at <a href="http://embryo-systems.info">http://embryo-systems.info</a>. The source code is currently hosted on github and written in erlang.</blockquote>