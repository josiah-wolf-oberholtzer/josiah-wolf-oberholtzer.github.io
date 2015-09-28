---
layout:   page
title:    Discograph
excerpt:  "Visualizing music as a social graph"
category: code
---

Discograph is an interactive visualization of the relationships between
musicians, bands and labels.

All of Discograph's data is derived from the Discogs discography database:
nearly 4 million artists, 1 million labels, and 7 million releases creating a
network of nearly 70 million different relationships.

I designed and implemented Discograph with a little help from some great tools
and packages:

- Python 3
- MongoDB and mongoengine
- Peewee
- D3js and Bootstrap CSS
- Flask, Gunicorn and supervisor.d

[Live site](http://discograph.mbrsi.org)

[Source](https://github.com/josiah-wolf-oberholtzer/discograph)