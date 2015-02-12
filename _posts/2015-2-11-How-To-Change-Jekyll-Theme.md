---
layout: post
title: How to change jekyll theme
---

So you just installed Jekyll and got your blog running. But how to change the site's layout or theme. That's not so straightforward to do.

<h3>Jekyll themes</h3>
There is al kinds of nice Jekyll themes, most of them clean, minimal and functional. Check for example <a href="http://jekyllthemes.org/">Jekyllthemes.org</a> for a quick overview of some templates. And there is even a lot more themes worth checking out and are not listed there.

<h3>Requirements</h3>
<ul><li>Make sure you've got Jekyll <a href="http://jekyllrb.com/docs/installation/">installed</a>.</li>
<li>For easy testing check <a href="http://localhost:4000">localhost:4000</a> if you've got your site working locally.</li><li> If that's not the case, just type <code>jekyll serve</code> while in your site's directory</li> </ul>

<h3>Jekyll Bootstrap</h3>
With Jekyll Bootstrap it's pretty straightforward to change your theme. All you need to do is <a href="http://jekyllbootstrap.com/usage/jekyll-quick-start.html">install it</a>. Dir into the installation and change the theme with this one simple command.

<code>rake theme:install git="https://github.com/jekyllbootstrap/theme-the-minimum.git" --trace</code>

There is not many <a href="http://themes.jekyllbootstrap.com/">themes on bootstrap</a> (yet) but its ease of use is really nice. 

