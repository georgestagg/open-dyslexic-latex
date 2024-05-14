README
======

This is a version of the [Open Dyslexic](https://github.com/antijingoist/open-dyslexic/) font for LaTeX.

An example is included at `source/fonts/od/test.tex`.

Linux/TexLive
=========
 * Copy the contents of this repo into `~/texmf`. You might have to make the `texmf` directory.
 * Run the command: `mktexlsr ~/texmf`
 * Run the command `updmap-user --enable Map=od.map`
   * If this fails, try `updmap -user --enable Map=od.map` instead.
 * You're done! You can use Open Dyslexic in your documents by adding the line `\usepackage{od}` to your LaTeX preamble.
 
MacOS/MacTeX
============
 * Copy the contents of this repo into `~/Library/texmf`. You might have to make the `texmf` directory.
 * Run the command: `mktexlsr ~/Library/texmf`
 * Run the command: `mkdir ~/Library/texmf/web2c/`
 * Run the command: `touch ~/Library/texmf/web2c/updmap.cfg`
 * Run the command `updmap-user --enable Map=od.map`
   * If this fails, try `updmap -user --enable Map=od.map` instead.
 * You're done! You can use Open Dyslexic in your documents by adding the line `\usepackage{od}` to your LaTeX preamble.
