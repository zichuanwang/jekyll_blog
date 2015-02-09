---
title: Stock Investment Algorithm
layout: post
tags: jekyll blog
---

My friend asked me to help implement an algorithm for stock investment yesterday. To be honest, I know absolutely nothing about stock before. So it took me quite a while to learn the basic knowledge, such as [Keltner Channel](http://en.wikipedia.org/wiki/Keltner_channel) and short selling (this thing doesn't exist in mainland China). After a few hours of discussing and coding, I finally got my simulated result — 30% annualized return, if I'm buying Apple's stock. Great. See that's why I love coding. It helps you learn by practice, and I certainly get a better idea of how things really work in the stock market.

His algorithm is fairly simple. I'm going to share this idea in plain language. When the price raises through the Keltner avarage line, you buy in, and do short selling vice versa. The key idea here is when to sell. Rather than predicting when the price reaches peak, we only care about how it changes relative to the peak value. In my implementation, I sell 50% of my stock when the price drops 30% compared to the peak value, and I sell all of my stock when it drops more than 60%. There are other techniques in this algorithm, like re-buy in when the price exceeds Keltner high line. I'm not going to address those in this post. If you are interested, you can find my implementation on [GitHub](https://github.com/zichuanwang/stock_investment). It's far from mature, but it sure works in some aspects.