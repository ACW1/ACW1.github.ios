---
layout: post
title:  "Nieuwe post"
date:  2016-09-08
categories: jekyll update
---

To add *new* posts, simply add a file in the '_posts' directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

![Guignardplaatje](/assets/banner-guignard.jpg){:class="img-responsive"}
*Een schilderij van Guignard.*
<!-- ![image-title-here]({{ site.url }}/assets/banner-guignard.jpg){:class="img-responsive"} -->

<!-- ##### Met een onderschrift© -->

<!-- En een kleinere versie: ![Guignardplaatje](/assets/banner-guignard.jpg){: height="36px" width="36px"} -->

This is a text with a
footnote[^1].

[^1]: And here is the definition.

Mijn naam is A.C.W. van Kruining.

*[A.C.W.]: Arthur Christianus Wilhelmus

<div style="float: right; margin-bottom: 50px;">
Something that stays right and is not wrapped in a para.
</div>

A [link](http://kramdown.gettalong.org){: target="_blank"}
to the kramdown homepage. Wat gebeurt er met de rechterfloattekst wanneer deze tekst ook naar rechts uitwijkt vanwege verlengende lengte aen aanvullende woorden?

A [link][kramdown hp]
to the homepage.

[kramdown hp]: http://kramdown.gettalong.org "hp"

Dit is een gewone regel.

> Dit is een blockquote.

>> Dit is een geneste blockquote.

Hier komt een codeblokje:

    Codeblokje

~~~ ruby
def what?
  42
end
~~~

Hiermee maak je regellijnen:

~~~
* * *

---

  _  _  _  _

---------------
~~~

***

First level header
==================

# First level header

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
