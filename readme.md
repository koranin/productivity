# bash

- enable vim in terminal ([ref](https://unix.stackexchange.com/questions/4870/is-it-possible-to-have-vim-key-bindings-in-terminal))

  `set -o vi`

Command | Description
--- | ---
`exec bash -l` | switch between zsh and bash

## vscode

General | Description
--- | ---
`ls -ld .?*` | list hidden files


# vscode

### Common

Key    | Description
------ | -----------
⌘ p   | go to file
⌘ P   | command palette
⌘ ,   | settings
⌘ w   | close
⌘ .   | quick fix

### Basic editing

Keys       | Description
---------- | -----------------
⎇ ↑       | move line up
⎇ ↓       | move line down
⎇ ⇧ ↑     | copy line up
⎇ ⇧ ↓     | copy line down

Keys       | Description
---------- | ------------------
⌘ ⎇ ↑     | multi-select up
⌘ ⎇ ↓     | multi-select down

### Rich languages editing

Keys             | Description
---------------- | -----------
⌘k m            | change file language

### Editor

Keys      | Action Description
--------- | ----------------------------------
⌘ 123    | select `group` 1/2/3
^ ⌘ →    | move `editor` to left `group`
^ ⌘ ←    | move `editor` to right `group`
⌘w       | close `editor`
⌘k w     | close `editor`
⌘k ⌘w   | close `window`

### Markdown

Shortcut | Description
-------- | ---
⌘k v    | open markdown preview

## Display

Shortcut     | Description
------------ | ------------------
^ ⌘ f       | toggle full screen
⌘ b         | toggle sidebar
⌘ E         | explorer
⌘ F         | search
⌘ G         | source control
⌘ D         | debug
⌘ X         | extensions
⌘k v        | preview markdown
⌘k z        | zen mode

## vim

https://www.youtube.com/watch?v=_AOW5ThfI9Y

Command | Description
------- | --------------------------
~       | char: toggle case
s       | char: delete + insert mode
ysaw'   | word: surround with '
yss'    | line: surround with '
J       | line: join below
zt      | scroll: top
zz      | scroll: middle
zb      | scroll: bottom

ZZ save + close
E! close + discarted
(hello world)
. repeat last command
{ move up paragraph
} move down paragraph


### one window

Command | Description
------- | ---
y$      | copy to end of line
yaw or yiw ???  | copy word
p       | paste
P       | paste with space

### multiple windows

Command | Description
------- | ---
*y$     | copy to anther window
*p      | paste from another window

## github desktop

Command | Description
--- | ---
`cmd p` | push
`cmd P` | pull

### mac

Command | Description
--- | ---
`cmd shift esc` | force quit applications

### slack

Command | Description
--- | ---
`cmd k` | search use
