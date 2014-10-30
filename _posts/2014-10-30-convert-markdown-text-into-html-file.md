---
layout : post
title  : Convert Markdown text into HTML file
---
Go to this [link](http://daringfireball.net/projects/markdown/) and download the zip file. Uncompress it and copy **Markdown.pl** file into **/usr/local/bin** directory.

In **.vimrc** file, put in the following line:

    nnoremap <leader>md :silent !/usr/local/bin/Markdown.pl --html4tags % > output.html<CR>

That's it. From now on, whenever you want to export your Markdown to HTML format, just press your shortcut. **output.html** is your result.
