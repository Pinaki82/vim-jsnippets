# vim-jsnippets
Simple utility for managing snippets of text within vim.


Originnaly created by [Jeremy Cantrell](https://www.vim.org/account/profile.php?user_id=11888) as [snippets.vim](https://www.vim.org/scripts/script.php?script_id=2152) : Simple snippet storage and retrieval separated by filetype.

### Script Type

utility
 
### Description

Simple utility for managing snippets of text within vim. Users can add, edit, and delete snippets within vim. Command completion is supported in all places that make sense. A menu is also added at "Plugin/Snippets".


### Install Details:

Place the script in ~/.vim/plugin & place the text doc in ~/.vim/doc. Restart vim.

OR

With vim-plug:

`Plug 'https://github.com/Pinaki82/vim-jsnippets.git'`

`:PlugInstall`

## COMMANDS

AddSnippet -- adds new snippet that contain a range of lines

EditSnippet -- edits a snippet in a new tab

DeleteSnippet -- deletes a snippet (with confirmation)

InsertSnippet -- inserts a snippet before the current line

AppendSnippet -- inserts a snippet after the current line

ListSnippets -- lists snippets

# MAPPINGS (`<leader>` is set to `\`, by default)

`<leader>jsa` -- AddSnippet with current buffer (normal mode)

`<leader>jsa` -- AddSnippet with range of lines (visual mode)

`<leader>jse` -- EditSnippet

`<leader>jsd` -- DeleteSnippet

`<leader>jsp` -- AppendSnippet

`<leader>jsP` -- InsertSnippet

`<leader>jsl` -- ListSnippets

Create a directory $HOME/vimfiles/snippets. Create separate sub-directories for different file types (c, cpp etc.).

For example:

`%USERPROFILE%\PortableApps\gVimPortable\Data\settings\vimfiles\snippets`

`%USERPROFILE%\vimfiles\snippets`

`~/vimfiles/snippets`

Licence: https://www.vim.org/scripts/script.php?script_id=2152
