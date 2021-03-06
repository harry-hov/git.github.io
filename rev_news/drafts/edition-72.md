---
title: Git Rev News Edition 72 (February 24th, 2021)
layout: default
date: 2021-02-24 12:06:51 +0100
author: chriscool
categories: [news]
navbar: false
---

## Git Rev News: Edition 72 (February 24th, 2021)

Welcome to the 72nd edition of [Git Rev News](https://git.github.io/rev_news/rev_news/),
a digest of all things Git. For our goals, the archives, the way we work, and how to contribute or to
subscribe, see [the Git Rev News page](https://git.github.io/rev_news/rev_news/) on [git.github.io](http://git.github.io).

This edition covers what happened during the month of January 2021.

## Discussions

<!---
### General
-->

<!---
### Reviews
-->

<!---
### Support
-->


## Developer Spotlight: Taylor Blau

* Who are you and what do you do?

  I am Taylor. I work at GitHub, where I spend most of my time
  contributing to the Git project.

* What would you name your most important contribution to Git?

  I'm still submitting many of the patches, but I think multi-pack
  reachability bitmaps will be my most important contribution to Git so
  far.

  If they work, they'll allow hosting providers who rely on reachability
  bitmaps more flexibility to control when and how they repack their
  repository. If you want to use bitmaps, you have no choice but to
  repack your repository into one enormous pack. Multi-pack reachability
  bitmaps mean that you won't have to, and can instead repack your
  repository however you want.

  If I'm limited to things that I have finished, I would say that the
  [on-disk reverse index](https://public-inbox.org/git/cover.1612998106.git.me@ttaylorr.com/)
  is another good one. But that's kind of cheating, since it's related
  to multi-pack bitmaps ;).

* What are you doing on the Git project these days, and why?

  Most of my time is spent working on multi-pack bitmaps. There are a lot
  of different topics in [my fork](https://github.com/ttaylorr/git) that
  all need to get merged in order to  make this feature work. So, I'm
  spending my time in all of the usual ways: submitting patches, responding
  to review, submitting more patches, and so on.

  When I'm not doing that, I enjoy to read and review patches from other
  folks on the list. I feel like there is a lot of exciting work going on
  recently, and so I'm always interested.

  Every release or so I have the pleasure of writing a
  ["release highlights" blog post](https://github.blog/author/ttaylorr/)
  that GitHub publishes. We're still a few weeks away from a release
  (at the time of writing), so it's not something that I'm working on yet,
  but it will come up soon enough.

* If you could get a team of expert developers to work full time on
  something in Git for a full year, what would it be?

  I'm not sure :). I care a lot about performance on large repositories,
  so I think that if I were in charge of such a team, that I would just
  set them loose to explore the boundaries of what's possible, and push
  them further.

* If you could remove something from Git without worrying about
  backwards compatibility, what would it be?

  Gosh, I would love to get rid of `.keep` packs, or at least the
  distinction between in-core and on-disk ones. They're incredibly useful,
  but they are subtly different, in ways that are sort of hard to reason
  about.

* What is your favorite Git-related tool/library, outside of Git itself?

  I use [`tig`](https://jonas.github.io/tig/) often, particularly its
  blame and log view. Michael Haggerty's [`git when-merged`](https://github.com/mhagger/git-when-merged)
  is another indispensable tool in my workflow.

  I'm curious to try Stephen Jung's [`git absorb`](https://github.com/tummychow/git-absorb)
  tool, but I haven't gotten to it yet.


## Releases


## Other News

__Various__


__Light reading__


__Git tools and sites__


## Credits

This edition of Git Rev News was curated by
Christian Couder &lt;<christian.couder@gmail.com>&gt;,
Jakub Narębski &lt;<jnareb@gmail.com>&gt;,
Markus Jansen &lt;<mja@jansen-preisler.de>&gt; and
Kaartic Sivaraam &lt;<kaartic.sivaraam@gmail.com>&gt;
with help from XXX.
