# Viewfinder/iPad i18n #

This project is for people interested in helping to internationalize Viewfinder for iPad. I18n for Viewfinder is done entirely though .strings files. There is no XIB localization involved. If you can use Git and edit a text file, you can help.

There is a [mailing list to discuss any issues](http://lists.connectedflow.com/mailman/listinfo/i18n).

## Current Language Maintainers ##

* Chinese
* Dutch - [Vincent Driessen](http://github.com/nvie)
* English - [Fraser Speirs](http://github.com/fspeirs)
* French - [Cyril Godefroy](http://github.com/cgodefroy)
* German - [Chris Kau](http://github.com/chriskau)
* Italian
* Japanese - [Fraser Speirs](http://github.com/fspeirs)
* Russian - [Fraser Speirs](http://github.com/fspeirs)
* Spanish - [Victor Jalencas](http://github.com/victor)

## How to Help ##

1. Fork this project.
2. Edit the language you want to work on.
3. Send a pull request to [Fraser Speirs](http://github.com/fspeirs).

PS: Due to merging difficulty, please don't edit the spreadsheet.

## A note on Maps_1 and Maps_2 ##

In Viewfinder, the same word is used in more than one place in the app. The comment should be enough to explain the context - if it's not, let me know.

Any translation keys that end with an underscore and a digit are there to distinguish more than one usage of that word in the UI. For example, each photo has a "Map" item in the info popover that leads to a map of the photo's location.  In that map view, there's then a segmented control for the different map types and the first segment is titled "Map".

In English, these different uses always end up being the same word but other languages may not.  It's OK if you end up with:

> `"Map_1" = "Map"`
> `"Map_2" = "Map"`

