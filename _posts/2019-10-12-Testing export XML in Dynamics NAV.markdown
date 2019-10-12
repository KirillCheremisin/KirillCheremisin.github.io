---
layout: post
title:  "Testing export XML in Dynamics NAV"
date:   2019-10-12 00:00:00 +0300
categories: jekyll update
author: Kirill Cheremisin
---

Hi there!

In short, the article is dedicated to covering export XML with automated tests.
In the article I describe how to test export, how can you get automated tests usefull while refactoring or expanding functionality, how to expand existing functionality without breaking it down.

The most important points:
1. Tests help you to keep covered functions working;
2. Use events to skip unnecessary behaviour;
3. Use manual event subscriptions in tests;
4. Divide work to small steps (the code above could be refactored into smaller pieces with the help of tests);
5. Use buffered data to allow the use of functionality from different places.

The whole article with the screens and pictures you can read [here][medium-link].

[medium-link]: https://medium.com/@cheremisin_k/testing-export-xml-in-dynamics-nav-6aa85bb7f7c4?source=friends_link&sk=552cf7276f4d93ebad7e30d7b9c46e38