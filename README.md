![Logo](docs/img/logo.png "Logo")

SFCC Utilities
---

> Utilities for working with Salesforce Commerce Cloud

Introduction
---

This repo contains a collection of utilities that make interacting with Salesforce Commerce Cloud easier

Overview
---

#### Bookmarklets

Bookmarklets are scripts stored as a bookmark in your web browser, which allow you to interact with the currently loaded web page in some way.

##### Business Manager

* [`Show Unique Identifiers`](docs/bm-unique-ids.md)

  On pages such as Products, Content Assets, and Custom Preferences, clicking on this bookmarklet will show the unique IDs for each attribute.

* [`Share Business Manager Link`](docs/bm-share-link.md)
  
  Often URLs inside business manager will contain a CSRF query parameter.  Copying and sharing this link with others will result in the other user seeing an error regarding an expired CSRF. 
  When clicked, this bookmarklet will take the current webpagee URL, strip its CSRF, and copy the resulting URL to your clipboard 
