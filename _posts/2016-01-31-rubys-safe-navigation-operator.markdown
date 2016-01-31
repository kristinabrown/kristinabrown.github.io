---
layout: post
title:  "Ruby's Safe Navigation Operator"
date:   2016-01-31
categories: Software Engineering
---

Every Christmas (since 2013) a new version of Ruby is released into the world, and with it comes some
bug fixes, usually some performance improvements, and sometimes some fun and exciting new features.
With this latest release, the 2.3 release, came one of my new favorite things, the safe navigation operator.

The Ruby safe navigation operator which allows you to account for an object coming through as `nil`. So
everywhere in your application where you are checking if something actually exists before checking a second attribute of that object
can now be replaced with a more concise safe navigation operator chain. ex.

{% highlight ruby %}
#this not so uncommon nil check
obj && obj.fulfilled?

#becomes this more concise method call with a escape hatch
#if the object happens to not exist
obj&.fuflilled?
{% endhighlight %}


But as is the case with everything, with power comes responsibility. Now that Ruby gives us an easier way
to handle nil doesn't mean we can stop asking the tough questions, why would this object ever be nil, what does that mean
for everything that preceded this method call and what does that mean for everything that will come after it. It's the silent nil
failures I fear more than the big, loud, `undefined method 'blah' for nil:NilClass`.

I should also add that I love the new Ruby safe navigation operator, and I use it every day. ;)
