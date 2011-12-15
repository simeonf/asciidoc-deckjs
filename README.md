Asciidoc-deck.js
================

An asciidoc backend for deck.js


Dependencies
------------

* AsciiDoc
* deck.js

If you haven't download deck.js, you can download it using following command:

```bash
make isntall
```


Installation
------------

All you need to do is to make sure your asciidoc can properly find `deckjs.conf`. For asciidoc's configuration file loading strategy, please refer to [this guide](http://www.methods.co.nz/asciidoc/userguide.html#X7).

The easiest way is to put `deckjs.conf` and the asciidoc file you wrote in the same directory.


Usage
-----

```bash
asciidoc -f deck.js.conf file.asciidoc
```
file.asciidoc is the asciidoc file you wrote. 


