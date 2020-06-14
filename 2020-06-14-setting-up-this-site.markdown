---
layout: post
title:  "Setting up Jekyll Minima theme site on GitHub"
date:   2020-06-14 16:42:00 +0200
categories: posts
---
How did I set up this site?

On Ubuntu 18.04 LTS I installed `Ruby`, then `Jekyll` and `Bundler`:

`$ sudo apt install ruby`

`$ sudo gem install jekyll bundler`

Then I set up a Jekyll project (Minima theme) and turned that to a `Git` repostitory. The first command also created the project folder itself:

`$ jekyll new z10011.github.io`

`$ cd z10011.github.io`

`$ git init`

Then, I was able to edit the content of the my site.

To serve the site locally (previewing that before publising at `127.0.0.1:4000`) I used:

`$ bundle exec jekyll serve`

Once the site seemed to be ready to be published I pushed the files to my z10011.github.io repostitory on GitHub.
