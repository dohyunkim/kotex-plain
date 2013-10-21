kotex-plain
===========

Introduction
------------

kotex-plain is a package for typesetting Hangul, the native 
alphabet of the Korean language, using plain TeX engine.
kotex-plain belongs to ko.TeX, a comprehensive Korean typesetting 
system together with kotex-utf, kotex-oblivoir, cjk-ko, XeTeX-ko, 
LuaTeX-ko, and kotex-utils.

Usage
-----

To typeset Hangul, start your document as follows:

    \input kotexplain

You should use `etex` or `pdftex` commands to compile the document
since kotex-plain uses e-TeX primitives. Also keep in mind that 
Korean documents needs to be encoded in UTF-8.

To specify Hangul fonts, you can use the following methods:

* `\hfont{outbb}{at 12pt}: This command set the current Hangul font
as 12 point bold.  This is the most general way of specifying
Hangul fonts.
* `\hfontname{outbtb}: This is equivallent to `\hfont{outbb}{}`, which
only applies bold typeface to the current font.
* `\hfontsize{at 12pt}: This command changes the size of the current
font as 12 point. Same effect can be achieved by `\hfont{}{at 12pt}`.

To use CWEB system for literate programming, you can use hangulcweb.tex
as follows:

    \input hangulcweb


For more information, please refer to the document included with
kotex-utf package (written in Korean).

License
-------

kotex-plain is licensed under the LaTeX Project Public
License (LPPL).

Contacts
--------

Please report any errors or suggestions to the package maintainer,
Kihwang Lee <leekh@ktug.org>.

