---
layout: default
title: PouchDB, the JavaScript Database that Syncs!
---

<h1 id="the_database_that_syncs">The Database that Syncs!</h1>

<div id="home1">

<section>

PouchDB is a small embeddable Database written in Javascript and inspired by <a href="http://couchdb.com">Apache CouchDB</a>, it allows your application to store data locally so your applications always work even while offline and syncs that data online transparently so your users always have most up to date data possible.

<ul id="news">
  <li><small>25th August 2013</small> <strong>PouchDB Website Updated</strong></li>
  <li><small>1st May 2013</small> <strong>v0.1.0 Released</strong></li>
  <li><small>4th May 2013</small> <strong>PouchDB Students</strong></li>
</ul>

</section>

<section>

{% highlight js linenos %}
var db = new Pouch('dbname');

db.put({
 name: 'David',
 age: 66
});

db.changes({
  onChange: function() {
    console.log('Ch-Ch-Changes');
  }
});

db.replicate.to('http://example.com/mydb');
{% endhighlight %}

</section></div>


<div id="home2">

<section>Works in Firefox, Chrome, Opera, Safari and IE and Node.js</section>
<section>PouchDB is just a script tag and 65KB away in the browser, or npm install away in node </section>
<section>Get Started with PouchDB ></section>

</div>