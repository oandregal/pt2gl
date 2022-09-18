# pt2gl

A set of sed rules to convert portuguese words into galician ones.

It implements the rules suggested by the paper "[Dictionary aligment by rewrite-based entry translation](./dictionary-alignment-by-rewrite-based-entry-translation.pdf)" by Alberto Simões and Xavier Gómez Guinovart.

How to use:

```sh
cat input.file | sed -f pt2gl.sed > output.file
```
