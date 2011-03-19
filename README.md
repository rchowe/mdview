mdview - Markdown Viewer
========================

A simple command-line utility that opens a markdown file in your default web browser. Currently Linux only (as it uses <code>x-www-browser</code> to start the browser), but I intend to get around to fixing that one of these days.

You must have markdown installed on your system and in your path to use this tool.

Usage
-----

<pre>
mdview <i>markdown_file</i>
</pre>

Configuration
-------------

If you want to use a different stylesheet than the builtin, create a .mdview.css file in your home directory with the style you want to use.

License
-------

mdview is distributed under the BSD license. See the [LICENSE](license) file for more.
