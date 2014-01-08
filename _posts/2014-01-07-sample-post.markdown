---
layout: post
title:  "This is my sample post"
date:   2014-01-07 18:17:35
categories: sample post
---

Why hello there, let me do a sample ruby snippet.

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Here is another ruby highlight (this is really really funsies!)

I really like adding the lineos right here:

{% highlight ruby linenos%}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight linenos%}