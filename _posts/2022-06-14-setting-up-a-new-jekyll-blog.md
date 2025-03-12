---
layout: post
title: Setting up a new Jekyll Blog
date: 2022-06-14 12:00:00 -0600
categories: [General, Blog]
tags: [blog, Jekyll]
---
Knowing for a while now that I'd eventually need a website to showcase research, I've been on the lookout for solutions.  I currently use [Obsidian](https://obsidian.md) for a notes solution -- and I like it quite a bit.  It's introduced me to [Markdown](https://www.markdownguide.org/basic-syntax/), which has been very quick to learn.  Additionally, Obsidian allows for LaTeX-like math using [MathJax](https://www.mathjax.org) and has a great option for embedding code.  Did I mention it's free?  What isn't free however is Obsidian Publishing, which currently is $20 a month -- more than I pay for 2TB of cloud storage from Google.  This seems excessive for hosting what are essentially just text files (Obsidian files are stored as Markdown files).

I'd seen [other PhD students](http://jhamrick.github.io/quals/) use markdown sites hosted on GitHub for material related to comprehensive exams and thought that looked like a good idea.  Additionally, GitHub Pages uses Markdown, which would allow for easy cross-posting of my Obsidian notes (since they're already Markdown).

Unfortunately, someone already owned the URL for my name, so I bought PhDane.com and went about configuring the GitHub page as a custom domain.  Turns out there is a great static site generator - [Jekyll](https://jekyllrb.com/) - which is widely used and has a large number of [open-source themes](https://jekyllrb.com/docs/themes/) available for use.  I opted for using the excellent [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) theme, which also allows for MathJax and even Mermaid diagrams.  It integrates some Google Analytics features that I might jump into in the future.  I have no experience with Ruby (Jekyll is based on Ruby) or HTML/CSS and little experience with GitHub, but figured it out after a couple days.  [Jekyll Compose](https://github.com/jekyll/jekyll-compose), though run through the command line, makes the blogging experience a bit quicker.  Also, a [good spell checker](https://marketplace.visualstudio.com/items?itemName=ban.spellright) for your IDE can save you some time.


## Resources
If you're interested in setting up a site like this, I'd suggest this video...

<iframe width="560" height="315" src="https://www.youtube.com/embed/F8iOU1ci19Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

And here's the [issue that hung me up for a bit...](https://github.com/cotes2020/jekyll-theme-chirpy/issues/502)

If you're looking for a more basic site (that allows for more customizability without jumping into CSS), this video was fairly quick and straightforward.

<iframe width="560" height="315" src="https://www.youtube.com/embed/7SBXl94xNl8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---
Honestly though, [this 4-part series](https://www.youtube.com/watch?v=moJgWrD6dwg) is the best one I've seen so far.  Check out the accompanying website [here](https://evanwill.github.io/go-go-ghpages-b/).  Parts 3 and 4 were especially useful and new (to me).
<iframe width="560" height="315" src="https://www.youtube.com/embed/moJgWrD6dwg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="560" height="315" src="https://www.youtube.com/embed/xQsQwp-oqSA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="560" height="315" src="https://www.youtube.com/embed/BdhLjm4VUKc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><iframe width="560" height="315" src="https://www.youtube.com/embed/QW7BXZ78RgM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>