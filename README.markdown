# Fountain CLM for TextWrangler and BBEdit

[Codeless Language Modules](http://www.barebones.com/support/develop/clm.html) (CLMs) are plugins for [TextWrangler](http://www.barebones.com/products/TextWrangler/) and [BBEdit](http://www.barebones.com/products/bbedit/) that add syntax highlighting, code folding, and other capabilities for languages not natively supported by these programs.

[Fountain](http://fountain.io/) is a plain-text syntax for writing screenplays.  (The [Fountain syntax](http://fountain.io/syntax) is similar to that of [Markdown](http://daringfireball.net/projects/markdown/), a general-purpose syntax.)  Fountain files are designed to be very readable, but they can be easily converted to other formats (like PDF and FDX) using [Fountain-friendly applications](http://fountain.io/apps).

Nima Yousefi's [regular expressions for Fountain](https://github.com/nyousefi/Fountain) have been very helpful while working on this project.

## Features

- _Syntax Highlighting:_ Scene headings, sections, character elements, transitions, comments, and other important aspects of the script are highlighted.

- _Scene Navigation:_ Scene headings and sections are tracked and collected in the function pull-down menu of the navigation bar.

## Installation

If you're using TextWrangler, move `fountain-clm.plist` to `~/Library/Application Support/TextWrangler/Language Modules/`

If you're using BBEdit, move `fountain-clm.plist` to `~/Library/Application Support/BBEdit/Language Modules/`

Restart TextWrangler or BBEdit to complete the installation.