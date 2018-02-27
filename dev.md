## bash

enable vim in terminal ([ref](https://unix.stackexchange.com/questions/4870/is-it-possible-to-have-vim-key-bindings-in-terminal))

`set -o vi`

## vscode

General

Shortcut | Description
--- | ---
`cmd  p`| go to file
`cmd shift p` | command palette
`cmd ,` | settings
`cmd w` | close
`cmd .` | quick fix

Basic editing

Shortcut | Description
--- | ---
`alt up/down` | move line up/down
`alt shift up/down` | copy line up/down
`cmd enter` | insert line below
`cmd shift enter` | insert line above

Multi-cursor

Shortcut | Description
--- | ---
`cmd alt up/down` | multi-select

Rich languages editing

Shortcut | Description
--- | ---
`cmd k cmd x` | trim training whitespace
`cmd k m` | change file language

Editor management
Shorcut | Description
`cmd \` | split editor

File management

Shortcut | Description
--- | ---
`cmd w` | close
`cmd k cmd w` | close all

Display
Shortcut | Description
--- | ---
`cmd ctrl f` | toggle full screen
`cmd b` | toggle sidebar
`cmd E` | explorer
`cmd F` | search
`ctrl G` | source control
`cmd D` | debug
`cmd X` | extensions
`cmd k v` | preview markdown
`cmd k z` | zen mode 

## vim

Command | Description
--- | ---
`~` | char: toggle case
`s` | char: delete + insert mode
`ysaw'` | word: surround with '
`yss'` | line: surround with '
`J` | line: join below

### one window

`y$` copy to end of line
`p` paste

### multiple windows

`*y$` copy to anther window
`*p` paste from another window 