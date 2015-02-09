---
title: This Blog Framework Is Awesome
layout: post
tags: jekyll blog
---

I got the passion to start my own blog about a week ago. Yeah, I know I should do this a long time ago. I was aware of the benefits even before I went to college. I was just too lazy. Anyway, I finally got here and I want to share my experience in building this blog to help people who want to the same thing.

### Purchase your domain
I purchased this domain about a year ago. Initially I host it on [NoIP](http://noip.com), but later I found an issue when trying to delegate this domain to one of my website hosted on Heroku, so I transfered it to [DNSimple](https://dnsimple.com). It costs me around 20 bucks a year.

### Rent VPS
[Digital Ocean](https://www.digitalocean.com) seems to very popular these days. But I chose [Linode](https://www.linode.com) anyway because I knew it would work. Follow Linode's official tutorial to setup DNS [here](https://www.linode.com/docs/networking/dns/dns-manager). You may also want to configure ssh and add some basic secure protection to your server before you start working on the blog.

### Blog framework
It's really exhilarating seeing the evolution of blog frameworks. Previously we have only one choice — WordPress. I'm not saying I hate PHP, but I'm definitely not a bug fun of it. Now we have so many choices. I don't want to run a Ruby on Rails app on my Linode server which will highly likely exhaust the memory. So instead I chose the more concise framework [Jekyll](http://jekyllrb.com). Jekyll is modern, you can use MarkDown language to write blogs just like writing ReadMe pages on GitHub. Actually Jekyll is the very engine behind GitHub Pages.

 I found this [blog](http://rsms.me) listing on Jekyll's website, and I basically imitate his template. I rewrite his CSS file in SCSS though. It seems a little outdated to keep using plain CSS syntax nowadays. 

### Deployment
I followed this [post](https://www.digitalocean.com/community/tutorials/how-to-get-started-with-jekyll-on-an-ubuntu-vps). Basically you need to configure Nginx on the server and everything else is fairly easy because Jekyll only generates static webpages. You can skip the Capistrano part if you would rather directly log in to your server and run `jekyll build`.

You can find my blog's source code on [GitHub](https://github.com/zichuanwang/jekyll_blog).