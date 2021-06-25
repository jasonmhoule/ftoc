This plugin adds a family of `ftoc_` macros. These mimic the core [table-of-contents (TOC) macros](https://tiddlywiki.com/static/Table-of-Contents%2520Macros.html) but instead of specifying a `tag`, require `field` and `value` parameters:

- `field` is the name of a field to check in each tiddler
- `value` is the value in this field that sets the top level of the TOC

Just like the core TOC macros, these macros act recursively past the first level. (`field` is constant for the table, but `value` changes at every level based on tiddler title.) This allows for use of the powerful TOC macros without needing to clutter your tags.

A hosted TiddlyWiki5 with this plugin is available [here](https://jasonmhoule.github.io/ftoc/).
