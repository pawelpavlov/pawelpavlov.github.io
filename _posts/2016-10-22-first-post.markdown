---
layout: post
title:  "Hello (blog) world!"
date:   2017-10-22 11:49:45 +0200
categories: blog
---
Hi guys, this is my first site ever. I'll be posting here stuff about frontend development.

As you see the site is on github pages. I was looking for something simple. I was thinking about Wordpress but I found something better for my requirements - Jekyll.
Jekyll is a static site generator. It's supported by Github - I commit the Jekyll files, sass, htmls and js and after my checkin everything is being built by Github.
I can write my posts in Markdown and there's no need for backend - great!
Of course you can build Jekyll locally and check if everything is ok before checking in to Github, but for now this is so simple that I didn't have to do this.

This is also test post:
Here's some `highlighted text`

And some code snippet in Ruby:
{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll.
[jekyll-docs]: http://jekyllrb.com/docs/home