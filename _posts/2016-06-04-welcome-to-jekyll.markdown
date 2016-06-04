---
layout: post
title:  "How to make a blog with Jekyll"
date:   2016-06-04 13:48:38 -0400
categories: blog jekyll
---

# What is Jekyll?

Jekyll is a gem that facilitates the generation of static blog sites. GitHub Pages supports Jekyll, which allows developers to quickly create impressive blog sites for free!


# What is GitHub Pages?

GitHub Pages allows each developer with a GitHub account to create a static web site hosted from their GitHub repository.


# Okay enough definitions, how do I get started?

To start off, type `$ gem install jekyll` in your terminal to install Jekyll. 

Next, type `$ jekyll new your-site-name` to create a new Jekyll site. Jekyll will create a directory with the name you have 
given, and fill it with files and folders that follow Jekyll's directory structure. 

You can use `$ cd your-site-name` to change directories in to your site's directory. 

Once you are in your project folder, you can type `$ jekyll serve` to launch your server on <http://localhost:4000>.

For more information on setting up Jekyll visit [Jekyll](https://jekyllrb.com/).

To get started with GitHub Pages, go to [GitHub Pages](https://pages.github.com/).


# Writing blog posts

Jekyll's main purpose is to take text written in Markdown, or even plain HTML, and run it through layout files that transforms the way it looks on a web page. This makes writing sites with Jekyll very quick and easy.

If you are unfamiliar with Markdown, this is a great resource: [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

To make a new post, create a new file under the `_posts` folder, with the naming convention `YEAR-MONTH-DAY-title.markdown`. Next, include the [YAML Front Matter](https://jekyllrb.com/docs/frontmatter/) at the top of the file:

{% highlight markdown %}
---
layout: post
title:  "title"
date:   YEAR-MONTH-DAY HOUR:MINUTE:SECOND -TIMEZONE
categories: RELEVANT CATEGORIES
---
{% endhighlight %}

Next, start blogging! To see what your blog post will look like, visit <http://localhost:4000> after you have launched your local server.

That sums up the basics of creating a blog with Jekyll! Check back soon for an update on how to add a portfolio to your Jekyll blog site.

