---
layout:     default
title: Contribute to DataMapper
created_at: Wed Aug 29 20:37:00 +0930 2007
---

{{page.title}}
==============

DataMapper is always looking for more contributors. When you've got an itch to
scratch, jump in and contribute! Write a few specs showing us how your code
works, create a patch and [submit it](http://datamapper.lighthouseapp.com/projects/20609-datamapper/)
as a new ticket or a fix for an existing one. After a few patches and many thanks, you'll
get commit access.

We benchmark all but the most trivial of patches, because we care about
performance and you should too!

What we need
------------

Currently DataMapper needs help in a few particular areas:

* API Documentation (using the [YARD documentation style](http://www.yardoc.org/more))
* Tutorials
* Code contributions
* Bug Reports

Git - Edge DataMapper
---------------------

DataMapper development uses [Git](http://git-scm.com) SCM. Please see [using git](using-git.html)
to learn how to contribute.

{% highlight bash %}
$ git clone git://github.com/datamapper/dm-core.git
{% endhighlight %}

Code Style Guidelines
---------------------

When contributing any code to DataMapper, please follow these guidelines.

1. Spec first. Spec thoroughly. (DataMapper is written with [RSpec](http://rspec.info/))
2. Parentheses around parameter lists for methods
3. Two space indent - not tabs!
4. Documentation is required (use the [YARD documentation style](http://www.yardoc.org/more))

*[YARD]: Yet Another Ruby Documentation (tool)
