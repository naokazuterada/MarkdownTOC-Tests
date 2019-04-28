# The Lemon Parser Generator

Lemon is an LALR(1) parser generator for C. It does the same job as "bison" and "yacc". But Lemon is not a bison or yacc clone. Lemon uses a different grammar syntax which is designed to reduce the number of coding errors. Lemon also uses a parsing engine that is faster than yacc and bison and which is both reentrant and threadsafe. (Update: Since the previous sentence was written, bison has also been updated so that it too can generate a reentrant and threadsafe parser.) Lemon also implements features that can be used to eliminate resource leaks, making it suitable for use in long-running programs such as graphical user interfaces or embedded controllers.

This document is an introduction to the Lemon parser generator.

<!-----------------------------------------------------------------------------
Original document downloaded on 2019/04/23 from SQLite website:
    https://sqlite.org/src/doc/trunk/doc/lemon.html

Converted from html to GFM by Tristano Ajmone for the "Lemon Grove" project:
    https://github.com/tajmone/lemon-grove

Last edited: 2019/04/24
------------------------------------------------------------------------------>

-----

**Table of Contents**

<!-- MarkdownTOC autolink="true" bracket="round" autoanchor="false" lowercase="only_ascii" uri_encoding="true" levels="1,2,3,4" -->

- [The `%code` example](#the-code-example)
- [The `%code` example with another `%code`](#the-code-example-with-another-code)
- [`%code` is first](#code-is-first)
- [The last `%code`](#the-last-code)

<!-- /MarkdownTOC -->

-----

#### The `%code` example

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


#### The `%code` example with another `%code`

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


#### `%code` is first

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


#### The last `%code`

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
