# vim_tutorial

Ack
====
```vim
:Ack searchword directory
```  
You can use individual buffers with `:bd`


Snipmate
====
Snipmates use filetype sensitive. If editing 


VimSurround
=====
To surround a text object with e.g. brackets: `ysiw}`
Yank Surround Inside Word Bracket.

Navigation Tips
=====

Tabs can be swithched with the following commands

```vim
gt #Next Tab
gT #previous Tab
```  

Editing Tips
=====

If I want to surround with grouping symbols as `""`, do the following: `x$p` This pastes at the thing at the end of the line. `xEp` also works for pasting at the end of the word.

http://stevelosh.com/blog/2010/09/coming-home-to-vim/#ack
https://www.youtube.com/watch?v=BGqBFA0t768


```vim
yiw    # yank inner word (copy word under cursor, say "first").
       # Move the cursor to another word (say "second").
viwp   # select "second", then replace it with "first".
       # Move the cursor to another word (say "third").
```


