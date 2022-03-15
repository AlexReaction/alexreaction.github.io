---
layout: post
title: A quick look at URL shortening
---

<h3>URL-Shortening</h3>
You may have seen URLs with the beginning *"Ad.fly", "Bit.ly", "Goo.gl"* and many more.
Those addresses are URL or link shortener.
<!--more-->
They help you to create short URLs by
providing a very short URL which then redirects you to the original website. I will explain the process 
later in my blog post.

<h3>What is a URL shorter</h3>
Simply spoken a URL shorter converts a long URL that you provide to the service and returns you
a much shorter URL which you can then use.

<h3> Why would you use a URL shortener?</h3>
There are multiple reasons to use link shortener. The most common reason is to save characters 
in character limitated text fields. By converting a long url you can save some characters and write
more text. Another reason is to convert ugly and long url into good looking and short url which
are much more pleasing. I won't talk about this topic right now but one always should be conscious about
the security risks that are involved. Hackers can easily hide malicious links behind short links. This
short link can be used to trick a subject into clicking a malicious link later on. 

<h3>How does a shortening service work?</h3> 
URL shortener are very simple. I won't cover security aspects here so I will just
explain the basic idea. A URL shortener save the url that you entered in a database and returns a key
that is associated with the url. This key is appended to the end of the shorted url. Once a user (you)
requests a url the key in taken from the url and is passed to the database query which then responds
with the original (long) url. You as the user are then redirected to the correct page.

<br>
<br>
<small>This article is still under reviews and might be edited.</small>


