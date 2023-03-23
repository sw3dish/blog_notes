# Vim notes

## 2023-03-16
- To repeat a character X to a certain column Y
  - `250A<X><Esc>d<Y>|`
- To add filetype specific settings
    - Make sure `filetype plugin on` is in `.vimrc`
    - Add code to `.vim/after/ftplugin`
        - Using `setlocal`
