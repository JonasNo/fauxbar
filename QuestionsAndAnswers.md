# Fauxbar's Frequently Asked Questions #




---


# General questions #

## What does Fauxbar do? ##

Fauxbar makes your web-browsing experience more enjoyable.

Acting as a companion extension for Google Chrome, Fauxbar lets you quickly and accurately locate your:
  * bookmarks,
  * history,
  * top websites,
  * search engines,
  * currently opened tabs,
  * apps,
  * extensions, and
  * commonly-used Chrome options and pages.

Fauxbar focuses on accuracy, convenience and speed to give you what you want, saving you time.

If you find Chrome's Omnibox's behavior frustrating, or don't like wading your way through Chrome's wrench menu, Fauxbar is for you.


---


## What's wrong with Chrome's Omnibox? ##

Chrome's Omnibox is often confusing and unhelpful.

Common frustrations and complaints regarding the Omnibox's behavior include:
  * Failure to display bookmarks or pages you know you've been to before
  * Displaying search suggestions higher than your desired page
  * Displaying infrequently-visited pages higher than your desired, frequently-visited page
  * Inability to search your bookmarks and history using certain non-alphanumeric characters
  * Failure to auto-complete the address you're currently typing, even though you've been to it before
  * Lack of a drop-down list to visually select the search engine you'd like to use
  * Hard-to-read results, with page titles and URLs being lumped on single lines with no site-specific favicons
  * A small, limited number of results can only be shown at once

Whenever Chrome's Omnibox fails to give you what you're after, it wastes your time.

Fauxbar, on the other hand, makes up for Chrome's shortcomings.


---


## How does Fauxbar save my time? ##

To make up for the aforementioned issues, Fauxbar provides you with an alternative to Chrome's Omnibox: a locally-stored page that primarily acts like Firefox's Awesome Bar.

Unforunately, the Omnibox can't be completely changed by a Chrome extension, so this is the next best solution.


---


## What's wrong with Firefox? ##

Although Firefox's Awesome Bar is quite possibly the epitome of the "find what you're after" browsing experience, Firefox itself is arguably rather unstable these days.

Firefox often hangs, freezes and takes too long to shut down, and you have to restart the whole browser just to enable or disable an add-on.

After suffering from these frustrations time and again, you could say that using Firefox wastes more time than it's worth.


---


## So why was Fauxbar developed for Chrome? ##

Chrome is arguably very stable, is always on the bleeding edge of new web technologies, and provides a great API for building extensions (although it would be nice if its Omnibox could be opened up a bit more).

By combining Firefox's usability with Chrome's stability, an enjoyable browsing experience can be had once again.


---


# Specific questions #

## What are Fauxbar's system requirements? ##

Fauxbar requires Google Chrome version 16 or higher to run.

And with Chrome, Fauxbar can be run on Windows, Mac OS or Linux.


---


## What's the difference between Fauxbar and Fauxbar Lite? ##

Fauxbar replaces Chrome's New Tab page; Fauxbar Lite does not.

Ideally, the option to replace Chrome's New Tab page or not would be bundled into just the one Fauxbar extension, but due to Chrome's extension API limitations, this option can not be toggled by an extension; it is unchangeable, hard-coded into each extension.

Fauxbar Lite was created to make up for this limitation.


---


## What is Fauxbar Memory Helper? ##

Fauxbar (and Fauxbar Lite) suffer from a memory usage bug. Memory usage gradually grows each time you browse to a page or open a tab, and is most noticeable over long periods of time (memory usage can typically rise from 20 MB to 70-120+ MB in an extended browsing session). The cause is yet to be determined.

As an interim "fix", Fauxbar Memory Helper is a Chrome extension that disables and re-enables Fauxbar (or Fauxbar Lite) when your computer has been idle for ~60 seconds, effectively resetting Fauxbar's (or Fauxbar Lite's) memory usage, but without interrupting your Fauxbar experience.

It is impossible for an extension to disable and re-enable itself on its own, so Fauxbar Memory Helper is a temporary solution. This extension is not required, but is available if you'd like to have it.

Hopefully, this cause of this bug will be found and fixed one day, but at least this is only a minor bug.


---


## Where can I download Fauxbar? ##

The various Fauxbar extensions can be downloaded from the Chrome Web Store:
  * [Fauxbar](https://chrome.google.com/webstore/detail/hibkhcnpkakjniplpfblaoikiggkopka)
  * [Fauxbar Lite](https://chrome.google.com/webstore/detail/bfimmnpbjccjihohjkimphfmmebffbmk)
  * [Fauxbar Memory Helper](https://chrome.google.com/webstore/detail/domhiadbdhomljcdankobiglghedagkm)


---


## How do I upgrade Fauxbar? ##

If you already have Fauxbar, Fauxbar Lite, or Fauxbar Memory Helper installed, and a new update has been released, you can either wait for Chrome to automatically install the update within a few hours, or:

  1. Go to **chrome://chrome/extensions/**
  1. Click **Developer mode**
  1. Click **Update extensions now**


---


## What are Fauxbar's main features? ##

Fauxbar's main page contains:
  * Address Box
  * Search Box
  * Site tiles
  * App tiles
  * Menu bar

The Address Box lets you search for a bookmark or page in your history, or use a specific search engine that has been added to Fauxbar.

The Search Box also lets you use a search engine. (the Search Box can be disabled in Fauxbar's options, if desired)

Site tiles provide thumbnails of your most visited sites. You can also manually choose which sites to show.

App tiles let you launch your installed Chrome apps.

The menu bar provides handy shortcuts to your currently opened tabs, recently-visited webpages, your entire bookmark tree, your apps, your extensions, and most of Chrome's special pages (like the Downloads page, or Chrome's Plug-ins page).

Fauxbar also has over 120 configurable options, so you can customize everything to your liking.


---


## Why does Fauxbar index my history and bookmarks? ##

When Fauxbar is first installed, Fauxbar creates its own index of your history and bookmarks, so that your history and bookmarks can be queried and ranked effectively within Fauxbar. After the initial index is created, Fauxbar silently updates its index on-the-fly as you browse.


---


## How does Fauxbar rank my bookmarks and history items? ##

Fauxbar uses Mozilla's [frecency algorithm](https://developer.mozilla.org/en/The_Places_frecency_algorithm) (the same algorithm that Firefox uses) to determine the importance of your bookmarks and history:

> <i>Frecency is a score given to each unique URI ... encompassing bookmarks, history and tags. This score is determined by the amount of revisitation, the type of those visits, how recent they were, and whether the URI was bookmarked or tagged.</li></ul>

<blockquote>The word "frecency" itself is a combination of the words "frequency" and "recency."</i></blockquote>

<hr />

<h2>How do I disable the Search Box or Address Box?</h2>

The Search Box and Address Box can be toggled via Fauxbar's Options > General > Input Boxes.<br>
<br>
<hr />

<h2>How do I use Fauxbar from Chrome's Omnibox?</h2>

To use an Omniboxified version of Fauxbar's Address Box, focus Chrome's Omnibox and press <b>F+Spacebar</b>, then type to find your desired bookmark or history page.<br>
<br>
<hr />

<h2>How do I add a keyword to a webpage?</h2>

To add a keyword to a webpage, type to bring up your page in the Address Box's result list, then right-click on the desired result, then click <b>Add Keyword</b>, enter a keyword and click OK.<br>
<br>
Then, when you start typing the keyword, the keyworded page will always appear first in your result list.<br>
<br>
<hr />

<h2>Are Fauxbar's options synced between installations?</h2>

Currently, Fauxbar's options are not synced between installations. This feature is planned for a future release, however.<br>
<br>
<hr />

<h2>How do I export Fauxbar's options?</h2>

Fauxbar's options can be exported and imported via Fauxbar's Options > Management > Options.<br>
<br>
<hr />

<h2>How do I submit a suggestion or bug report?</h2>

If you have a great suggestion for Fauxbar, or have stumbled across a bug, please view <a href='http://code.google.com/p/fauxbar/issues/list'>Fauxbar's current issues</a> to see if the issue already exists. Please also search for your issue to see if it's been covered before.<br>
<br>
If the issue exists, you may wish to "star" the issue, to signal that you're interested in getting this issue sorted, and to receive updates on the issue.<br>
<br>
But if the no issue exists for your suggestion or bug report, please <a href='http://code.google.com/p/fauxbar/issues/entry'>submit a new issue</a>.<br>
<br>
<hr />

<h2>Why the name "Fauxbar"?</h2>

Since it's impossible to add or modify a bar to Chrome's UI, Fauxbar's "bar" is merely part of the extension's HTML page. So really it's a fake bar, or a faux bar.<br>
<br>
<hr />

<h2>What is Fauxbar's logo supposed to be?</h2>

It's a red panda. A faux fox, if you will.