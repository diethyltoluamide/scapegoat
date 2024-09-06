# scapegoat
scapegoat is a clean way to write config. Compiling to JSON and back, scapegoat gives an extension of features you can't get otherwise.
# Syntax
The syntax of scapegoat is a little weird at times, but it's by no means hard.
### Parents
Everything in scapegoat has a parent. It's just a string with a colon.
```
foo:            <- parent
  bar = baz;    <- child
```
### Strings
Strings can be any alphanumeric characters, plus a few special characters.
```
abcdefghijklmnopqrstuvwxyz
ABCDEFGHIJKLMNOPQRSTUVWXYZ
0123456789_
```
