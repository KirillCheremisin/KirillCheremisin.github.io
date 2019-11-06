---
layout: post
title:  "Complicated data transfer in Dynamics NAV"
date:   2019-11-07 00:00:00 +0300
categories: jekyll update
author: Kirill Cheremisin
---

Hi there!

The problem is how to transfer lots of data in Dynamics NAV between objects in complicated scenarios.

In short, the article is dedicated to the method of making easier developing scenarios which use complicated data structures with lots of tables and variables. I describe how to gracefully and simple handle this situation.

The answer is use "data storage" (my brand-new name) codeunits. The details is under [link][medium-link].

[medium-link]: https://medium.com/@cheremisin_k/complicated-data-transfer-in-dynamics-nav-d519f3797565?sk=1b55b7ac2c369981deb95ca4d1260eec