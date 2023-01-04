+++
title = 'Hugo Pages from Data (de)'
date = 2023-01-01T13:20:06-08:00
draft = false
+++

This multilingual site builds pages from data, based on an [article] by [Regis Philibert] of [The New Dynamic]. You can pull in different data for each language if necessary.

[article]: https://www.thenewdynamic.com/article/toward-using-a-headless-cms-with-hugo-part-2-building-from-remote-api/
[Regis Philibert]: https://discourse.gohugo.io/u/regis/
[The New Dynamic]: https://www.thenewdynamic.com/

To build this site locally:

```text
git clone https://github.com/jmooring/hugo-pages-from-data.git
cd hugo-pages-from-data
hugo -s prebuild && hugo server
```
