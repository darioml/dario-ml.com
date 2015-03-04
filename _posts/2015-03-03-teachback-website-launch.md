---
layout: post
title: TeachBack - New Website Launch
description: "New Jekyll website launched for teachback"
modified: 2015-03-03
tags: [teachback, webdev, jekyll]
image:
  feature: http://teachback.co.uk/images/team_hunk.png
  credit: teachback
  creditlink: http://teachback.co.uk/
---

It's been on my to-do list for a while now, but [TeachBack](http://teachback.co.uk) now finally has moved away from a wordpress installation to github pages & jekyll. Now, I'm able to push the *ever so infrequent* blog posts to the website without having to remember **another** set of login deatils[^1], dynamically give permissions, and easily work on the website without bothering with custom wordpress plugins.

[^1]: Oh, and I'm also now not paying $12/month for a VPS to hold a wordpress website!

The move was fairly painless. I've [previously](https://github.com/darioml/votepascal.com) worked [on jekyll](http://labs.hailocab.com/), but I felt I couldn't give enough effort to design a website in an evening. I came across a great theme from [Michael Rose](http://mmistakes.github.io/minimal-mistakes/), which needed only a few mods to adapt it to our needs. I manually moved over the few blog posts from our wordpress installation (thought I'm sure something great such as [this](https://github.com/benbalter/wordpress-to-jekyll-exporter) could be used for a larger moved), and hit `git push`. 

Voila!

I can only but recommend using Jekyll for blogs and semi-static websites[^2]. The flexibility and simplicity it offers (*ignoring ruby*) surpasses anything else I've worked with. Add on top of that the bonus of not having to worry about deployment, and there is nothing to dislike. 

[^2]: Posts, comments, etc are all possible. Limitations come in when you need to write customer server software or interact with a database.
