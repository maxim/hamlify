hamlify
========

This tool will convert your html/erb to haml better than html2haml alone.

Problems fixed:

- IE comments parse correctly.
- Single-line indentations are moved on the same line as parent.
- Non-output HAML blocks are fixed. (ie `- end` is removed and block indentation fixed)

install
---------

    sudo gem sources -a http://gems.github.com
    sudo gem install maxim-hamlify

usage
------

    hamlify path/to/file.html.erb