> spreadsheet

Original code based on this [tutorial][tutorial].

First demo that allows expressions (like `A1 + B1`) in
[spreadsheet.html](spreadsheet.html); you can see it live at
[glebbahmutov.com/spreadsheet/spreadsheet.html](https://glebbahmutov.com/spreadsheet/spreadsheet.html)

Second demo implements simple HTML tags and live HTML binding
to make the reactive spreadsheet a mini "web app".
See the live result at
[glebbahmutov.com/spreadsheet](https://glebbahmutov.com/spreadsheet).
You can edit every cell and see the change propagate through the cells,
initially the cells are like this

```
A1 = 1
B1 = 2
A2 = 'A1 + B1'
HTML1 = '<i>A1</i> + <i>B1</i> = <b>A2</b>'
LIVE1 = 'HTML1' // but linked into the cell as HTML
```

[tutorial]: http://blog.thomasstreet.com/post/129096073308/building-a-spreadsheet-in-20-minutes-with-angular-js

### Small print

Author: Gleb Bahmutov &copy; 2016 based on work by
[David Graunke](https://twitter.com/graunked)

* [@bahmutov](https://twitter.com/bahmutov)
* [glebbahmutov.com](http://glebbahmutov.com)
* [blog](http://glebbahmutov.com/blog/)

License: MIT - do anything with the code, but don't blame me if it does not work.

Spread the word: tweet, star on github, etc.

Support: if you find any problems with this module, email / tweet /
[open issue](https://github.com/bahmutov/spreadsheet/issues) on Github
