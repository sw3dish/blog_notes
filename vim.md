# Vim notes

## 2023-03-16
- To repeat a character X to a certain column Y
  - `250A<X><Esc>d<Y>|`
- To add filetype specific settings
    - Make sure `filetype plugin on` is in `.vimrc`
    - Add code to `.vim/after/ftplugin`
        - Using `setlocal`

## 2023-03-23
- <C-o>/<C-i> in normal mode navigates around the jump list
    - jump list is across vim instances!
- To move around, cut, copy, paste in a terminal, switch to Terminal Normal Mode
    - `<ctrl>w N`:w
    - Once done, use `i` or `a`
