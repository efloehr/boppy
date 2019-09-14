Balance of Power 1990 source code from:
https://www.erasmatazz.com/library/source-code/index.html

Conversion from old Mac to Linux source files (change carriage return to line feed):
```bash
sed -zi 's/\r/\n/g' *
```

Options to convert the Pascal code by hand:
1. Hand convert
1. Build regex conversions
1. Build a Pascal parser/lexer and converter

Chose building a Pascal parser/lexer and converter... more interesting, fun, and
potentially useful to convert other Pascal programs.

David Beazley's SLY
https://github.com/dabeaz/sly
https://www.youtube.com/watch?v=zJ9z6Ge-vXs

