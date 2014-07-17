Where to buy electronics in Toronto?
------------------------------------

A listing of local and online electronics &amp; hardware retailers specifically for Toronto-area makers.

## About

This site was put together by Pearl Chen to make sure that you can find hobby electronics supplies in Toronto.

## Contribute

The retailers listing is part of a [Github repo](https://github.com/pchen/electronics-shopping-toronto) and I accept pull requests. For minor changes, go ahead and submit the PR. For more major ones, please open up a [Github issue](https://github.com/pchen/electronics-shopping-toronto/issues) for discussion.

### Preview site locally

[Install Jekyll](http://jekyllrb.com/docs/installation/) (requires Ruby):

```
$ gem install jekyll
```

Run the Jekyll server:

```
$ jekyll serve --watch
```

Go to **http://localhost:4000**.


### To add a Toronto or GTA retailer

1. Create a new Markdown (.md) file in the **_toronto_retailers** folder. Give it a file name representing the store's name (all in lowercase, separate spaces with an underscore). If a store has several locations, consider making an entry for each location so there's a snazzy Google Map for each one. 

2. All local retailers have this format for their template:

```
---
layout: default
name:  "STORE NAME"
website: "http://STOREWEBSITE.com"
address: "STORE ADDRESS, Toronto, ON"
phone: "(STORE) PHONE NUMBER"
---

BLURB ABOUT THE STORE GOES HERE.

IT CAN BE MULTIPLE PARAGRAPHS BUT BEST TO BE SHORT & SWEET. (AND NO... IT SHOULDN'T BE WRITTEN IN ALL CAPS.)
```

### To add an online retailer

1. Create a new Markdown (.md) file in the **_online_retailers** folder. Give it a file name representing the store's name (all in lowercase, separate spaces with an underscore).

2. All online retailers have this format for their template:

```
---
layout: default
name:  "STORE NAME"
website: "http://STOREWEBSITE.com"
---

BLURB ABOUT THE STORE GOES HERE.

IT CAN BE MULTIPLE PARAGRAPHS BUT BEST TO BE SHORT & SWEET. (AND NO... IT SHOULDN'T BE WRITTEN IN ALL CAPS.)
```

## Roadmap

* [ ] Add CI to automatically deploy contents of **_site** folder to **gh-pages** branch
* [ ] Rewrite some content so be less opinionated and more factual 