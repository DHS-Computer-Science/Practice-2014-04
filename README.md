# Practice 2014 - 04: A Serious Reading Problem

## Background
Gandalf’s search for the history of the One Ring took him to the library of
Minas Babel, under the care of Archivist Borges. This library contains every
possible book - true and false, nonsensical and insightful - and Gandalf must
use all of this wisdom to find the true account of the Ring.

Given that there are C possible characters, W characters in a line, L lines on a
page, and P pages in a book, tell how many books are in the library of Minas
Babel, if each possible book appears exactly once.

For example, if the library were to contain books with 2 characters (a,b), 3
characters per line, one line per page, and one page per book, then the
following books would be in the library: aaa aab aba abb baa bab bba bbb

## Description

### Input
Each test case is on its own line, each of the form C W L P; all are
non-negative integers. The end of input is marked by a line of the
form ”0 0 0 0”, which should produce no output.

### Output
For each test case, output a new line containing a single integer, which
should represent the number of books in the library.

## Sample
### Input
```
4 2 2 2
4 3 2 2
0 0 0 0
```

### Output
```
65536
16777216
```
