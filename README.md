# Umbraco Resources

The goal of this repo is to gather useful resources around the web to help people start developing advanced projects with [Umbraco](https://umbraco.com/).

## Custom sections & backoffice extensions

### Custom section with Listview
[Great article by David Brendel](https://24days.in/umbraco-cms/2015/custom-listview/) explaining step by step how to recreate ListView in a Custom Seciton. [Whole code on Github.](https://github.com/Mantus667/ListViewForCustomSection)

### Custom section with UIOMatic
[UI-O-Matic](https://our.umbraco.org/projects/developer-tools/ui-o-matic/) allows you to auto generate an integrated crud UI in Umbraco for a db table based on a petapoco (the default ORM in Umbraco) poco. 
[Github](https://github.com/TimGeyssens/UIOMatic)
[Docs](http://uiomatic.readthedocs.io/en/stable/)
[Examples](http://www.nibble.be/)


## Multilingual websites
[Article by Jeroen Breuer](https://24days.in/umbraco-cms/2015/multilingual-vorto-nested-content/) explaining how to make 1-1 multilingual website wit Vorto and Nested Content. [Example project on Github.](https://github.com/jbreuer/1-1-multilingual-example)

## Working with Umbraco
[Explanation how to work with uSync in different scenarios](http://blog.jumoo.co.uk/2017/working-with-usync/) by one and only [Kevin Jump](https://twitter.com/kevinjump_)

## Examine 
[Overview & Explanation by Peter Gregory](https://our.umbraco.org/documentation/reference/searching/examine/overview-explanation)

[Example by Rasmus Fjord](https://24days.in/umbraco-cms/2013/getting-started-with-examine/)

[More documentation by Shazwazza](https://github.com/Shazwazza/Examine/wiki)

[External Indexes by Rasmus Fjord:](https://24days.in/umbraco-cms/2016/custom-data-and-examine-searching/) Getting custom data into a custom Examine index.
[Paging with Examine by Shazwazza](https://shazwazza.com/post/paging-with-examine/)

[Multindex Searching:](https://bszyman.com/blog/multi-index-search-in-umbraco-using-examine) Examine searching through all indexes.

## Querying 
[Getting umbraco content: comparison of methods to get umbraco content by Tim Payne](http://skrift.io/articles/archive/testing-the-performance-of-querying-umbraco/) tl;dr: avoid using Typed Search. Query with examine "Search" and take content with Umbraco.TypedContent(id).
