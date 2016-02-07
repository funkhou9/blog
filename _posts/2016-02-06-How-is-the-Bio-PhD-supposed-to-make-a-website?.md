---
layout: post
---

The biology PhD learns to program through graduate courses (if they're lucky), self-teaching, or
perhaps sitting in on undergraduate CS courses. In each case, the objective is to learn enough
programming to encapsulate biological datasets, manipulate them, and analyze them. 
*This amounts to playing with text*, **lots of text**, specifically a bunch of AGTC's or 012's or AB's

Relative to programming needed to analyze biological data, programming intended for web and app development
resembles some sort of black magic. I would argue that if you're taking the time to learn statistical or 
bioinformatic algorithms and the languages to implement those algorithms, it's worth also learning 
some black magic in order to communicate your accomplishments and your research.

Black magic takes time for the bio PhD to learn on their own. I've found that the best way for the bio
PhD to develop a hub for scientific accomplishments and blog posts is to use their (presumed) existing
knowledge of Git and GitHub. [GitHub Pages](https://pages.github.com) provides a great way for the bio
PhD to develop websites for themselves, their labs, or their projects.

Unless all you want is a "Hello World!" page, the best way to get started quickly is to use 
[Jekyll](https://jekyllrb.com), a blog-focused web framework that's used by GitHub Pages. Use the quick 
start instructions on the main page to make your first plain Jane Jekyll site.

To speed up things a little more, I recommend using a pre-existing Jekyll theme like the ones found
on [this site](http://jekyllthemes.org). For my site, I liked the look of 
[this theme](https://github.com/CloudCannon/Read-Only-Jekyll-Theme). Find the repo of the Jekyll theme
you like, and clone it using:

{% highlight bash %}
git clone https://github.com/CloudCannon/Read-Only-Jekyll-Theme
{% endhighlight %}

Make modifications to the content and flesh out your bio. This may be an opportunity to learn some
HTML. Most modifications to replace existing content with your own may be done by modifying
`index.html` in the root of your project directory. Changes I made include updating my name, bio,
introduction to the site, my skills and hobbies, and academic accomplishments. Some changes may be made
to `css/style.css` to change the colors of the page, resize image elements, and so on. I won't include
how to do each of those things here. Instead, it's an opportunity to learn *HTML* and *CSS*.

Once you've made modifications to your project, to inspect your work on a local server with:

{% highlight bash %}
jekyll serve
{% endhighlight %}

Ready to publish it online? I found this particular youtube video very helpful for publishing my Jekyll site
on GitHub Pages:

<iframe width="560" height="315" src="https://www.youtube.com/embed/qoQzIjGbfTg" frameborder="0" allowfullscreen></iframe> 





