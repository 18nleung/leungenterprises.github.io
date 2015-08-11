---
layout: post
title: First post!
author: Nathan Leung
comments: true
tags: [html]
---
Hey guys!  Jekyll is really cool!

{% highlight html %}
<!-- HTML -->

<p>Text goes here</p>
{% endhighlight %}
{% highlight jade %}
//- Jade

p Text goes here
{% endhighlight %}
{% highlight css %}
/* css */

p {
  color: purple;
}
{% endhighlight %}
{% highlight sass %}
// stylus

p
  color purple
{% endhighlight %}
{% highlight javascript %}
// Javascript (jQuery)

$('p').html('Hello!');
{% endhighlight %}

Wow!  Syntax highlighting is included!  Only thing missing is tags/categories.

[Disqus](http://disqus.com) seems to be a great commenting system.
