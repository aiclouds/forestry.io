---
title: 2018-05-28 00:00:00 +0000
date: 2018-05-28 06:24:44 -1100
publishdate: 2018-05-27 18:00:00 -1100
layout: single
aliases: []
authors: []
expirydate: ''
categories: []
headline: ''
description: ''
textline: ''
tags: []
cta:
  headline: ''
  textline: ''
  calls_to_action: []
weight: ''
images: []
draft: true

---
### Features

* **Cloudinary Support**
* **Data-file templates**
  * Data files can now use templates in the same way that pages can
* **Color-picker front-matter field added**
* **Text strikethrough ability added to editor**
* **OAuth login added to remote admin**

### Enhancements

* **Updated Groups, Group-list, and Blocks UI**
* **Configurable media paths**
* **Date fields can be displayed in UTC instead of local timezone**
* **Group-list “Add” button applies smart labels to pluralized group names**
  * (E.g "Add Person" to a people group-list )
* **Added info icons next to front matter field types**
* **Code-block input rules can take a language**
* **Front matter wysiwyg now supports Markdown**
* **Removed HTML wysiwyg**
* **Media settings moved to its own tab**
* **"Save" Button shows feedback when saving**

### Bug Fixes

* **Blocks:**
  * Blocks left aligned in all browsers
  * Fixed validation errors when saving empty blocks group
  * Wrap error messages
* **Media:**
  * Clearer errors when uploads fail
  * Fix for: cant see white images
* **Group lists:**
  * Validation fixes for malformed values
* **Organizations:**
  * Logo links back to the site's organization instead of to "My Sites"
* **Date Picker**
  * Fixed Safari issue where the date-picker would immediately close.
* **Number field**
  * Fix for: not validating if min/max was 0
* **Previews:**
  * Fixed issue where having a string value for a group causes previews to fail with no error
* **Auth:**
  * Email validation accepts longer endings