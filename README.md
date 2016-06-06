# LLED Quick Search Tool

A quick search tool to filter results in a div. With tasty live search. Designed specifically and lovingly for UBC's Department of Language and Literacy Education ([LLED](http://lled.educ.ubc.ca)).

Other departments / faculties / curious bystanders are welcome to use it too. Be sure to tweak it for your needs.

Thanks to metafizzy for the [isotope plugin](https://github.com/metafizzy/isotope)

## Implementation

Paste all the contents of the index.html file into the page you'd like to use this on. The *script* tags should be at the top of the pages as there is no *head* section in UBC's CMS. Add the contents of the search.js file to the page's JavaScript section or even the site's Global JS file. Place the style.css contents similarly, depending on whether you want it to be global styling or styling for a particular page only.

## Cheeky keyword / alternative word workaround

Users don't always search an exact word but this is a very simple, quick regex search - not an intelligent Google-esque search engine. To accomodate the fact that users might use different words, you can add potential alternative words within the *searchable-item* divs. Remember that as long as some text is in a searchable-item div, it can be found. To hide it, just give it the *hiddentext* class and you're good to go. The same is true for including keywords that you don't want to show, but want to make searchable nonetheless. This allows us to include a whole list of things that can be searched, but use simple CSS to hide them. Use with care - this is **not** an advanced search engine, it is simply a way to quickly find things on a page. (Without good old Ctrl+F).

![lled_quick_search](https://cloud.githubusercontent.com/assets/10469803/15833026/95fd4170-2bd9-11e6-820b-a7b29ab9ac9d.gif)
