---
layout: post
title:  "Switching the API to Python"
date:   2020-03-24 13:15:00 -0500
categories: [update]
tags: [pf2e, api]
excerpt_separator: <!--more-->
---
The title pretty much says it all!
<!--more-->

I really wanted to be able to write the API fully in Go, but the scraper I was using (Colly) wasn't quite designed to be used the way I was trying to use it. So instead I'll be pivoting to Python and BeautifulSoup. I'll have to rewrite everything basically from scratch, but I think it will be worth it in the end.