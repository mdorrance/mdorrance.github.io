---
layout: post
title:  "The Power of Community"
date:   2015-07-17 1
categories: community
tags: featured
image: /assets/article_images/2014-08-29-welcome-to-jekyll/desktop.jpg
---
I like to go to Meetups. What's a Meetup? Meetups are neighbors getting together to learn something, do something, or share something. In active startup communities or more urban areas Meetups are prevalent. Simply go to Meetup.com online and use your zipcode to find a Meetup in a subject that you are interested in. Ideally you will find a Meetup that is focused on your explicit business idea. Believe it or not, you are not alone in your quest for knowledge, camaraderie or validation. There are 7 billion people on the Earth, so you are bound to find someone like you.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

{% highlight js %}

<footer class="site-footer">
 <a class="subscribe" href="{{ "/feed.xml" | prepend: site.baseurl }}"> <span class="tooltip"> <i class="fa fa-rss"></i> Subscribe!</span></a>
  <div class="inner">a
   <section class="copyright">All content copyright <a href="mailto:{{ site.email}}">{{ site.name }}</a> &copy; {{ site.time | date: '%Y' }} &bull; All rights reserved.</section>
   <section class="poweredby">Made with <a href="http://jekyllrb.com"> Jekyll</a></section>
  </div>
</footer>
{% endhighlight %}


[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
