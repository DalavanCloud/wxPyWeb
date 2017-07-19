<!--
.. title: New wxPython Website
.. slug: new-wxpython-website
.. date: 2017-07-18 23:14:08 UTC
.. author: Robin
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
-->

> "The 2000s called, they want their website back..."

Not any more!  I finally gave the old clunky site back to the dinosaurs and
have implemented a brand new site, which you are gazing at now, using the
awesome static site generator [Nikola](https://getnikola.com/).  The new
site combines most of what was on the old site, plus a 
[news feed](/news/) (you're reading a news post right now) and I also 
resurrected my old [wxForty-Two blog](/blog/) from the wordpress graveyard 
and added it here too. Being a static site I no longer have to worry about the 
perpetual stream of wordpress security issues.

<!-- TEASER_END -->

There is still some style and template tweaking that I have planned, plus
some more content, but thanks to Nikola I am *a lot* further on than I
thought I would be by now. And since posts and content are edited in ReST
or Markdown it should be lots easier to keep things up to date and add new
content as needed.

For those who care about the details, I'm using a custom theme based on
Nikola's stock [bootstrap3](http://getbootstrap.com/) theme, using
[Mako](http://www.makotemplates.org/) for the template engine. I customized
the base template to enable adding the panels on the right side of the page
(or at the bottom if you are browsing on a phone.) I also created a
"shortcode" template that is used to inject the most recent news posts on
the front page, enabling a combination of, in Nikola's terminology, "page"
and "index". And of course there has been some CSS tweaks too. Fun stuff.
