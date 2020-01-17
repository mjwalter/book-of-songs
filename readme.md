You must have LuaLaTex installed.

You must have Lilypond installed.

To compile, run `lualatex --shell-escape Book\ of\ songs.tex`.

To test a single file, uncomment the `includeonly` line towards the beginning of `Book of songs.tex` and substitute the file of your choice.

To create the indices, run `makeindex indexname` for each index you would like to create. Then move those to the `indices` folder.
