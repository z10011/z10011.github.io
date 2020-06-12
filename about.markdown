---
layout: page
title: About
permalink: /about/
---

{% highlight python %}
text = input("Introduction: ")
{% endhighlight %}

The purpose of this site is to share some posts about technology, autonomous vehicles or coding. Beyond these there may be some `Python`, `C` and `Golang` codes in my public repositories on GitHub.

{% highlight python %}
def letter_frequency(*arg):
  d = {x: text.count(x) for x in text if 96 < ord (x) < 123}
  print (f"The most frequent letter in the text is '{max(d,key=d.get)}'.")
  print (f"It appears {d.get(max(d,key=d.get))} times.")

letter_frequency(text)
{% endhighlight %}
