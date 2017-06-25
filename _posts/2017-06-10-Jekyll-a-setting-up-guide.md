---
layout: post
title:  "Jekyll, a setting up guide."
date:   2017-06-10 00:20:12 -0500
categories: webServices
---
# Jekyll

Is a simple blog, static site generator for personal projects.  
Jekyll is written in Ruby.

## Installing

For installing Jekyll, we just need install some dependencies:

* Ruby: Programming language.

      sudo apt-get install ruby ruby-dev make gcc

* Gem: Package manager for Ruby.

      sudo apt-get install rubygems-integration

* Jekyll:

      sudo gem install jekyll bundler

## Creating a static web

Creating a new project on your local machine:

    jekyll new webApp
    
![jekyll-new][jekyll_new]

Then, install components:

    cd webApp
    bundle install

![jekyll-install][jekyll_install]

Finally, start the static web:

    jekyll serve

![jekyll-serve][jekyll_serve]

In your favourite browser, enter to `localhost:4000`:

![jekyll-localhost][jekyll_localhost]

You can navigate here, e.g. /about page:

![jekyll-localhost-about][jekyll_localhost_about]

[jekyll_new]:             /assets/webApp/jekyll/jekyll_new.png
[jekyll_install]:         /assets/webApp/jekyll/jekyll_install.png
[jekyll_serve]:           /assets/webApp/jekyll/jekyll_serve.png
[jekyll_localhost]:       /assets/webApp/jekyll/jekyll_localhost.png
[jekyll_localhost_about]: /assets/webApp/jekyll/jekyll_localhost_about.png
