# RT-Format

Format current line immediately in INSERT mode as soon as you press ENTER:

![picture](https://github.com/skywind3000/images/raw/master/p/pep/rtformat_4.gif)

## Features

- Format current line in real-time when you press ENTER.
- Seamless, no need to stop your work to run an extra command like `gq` or `:Neoformat`.
- When you are focusing on editing, everything is done without pay extra attention.
- No external process (eg. LSP servers) dependencies.
- Supported languages including: python, lua, ruby and javascript.

## Requirements

- Vim with "+python3" feature.
- Python module "autopep8".

## Quick Start

Install the plugin with vim-plug:

```VimL
" Tell vim-plug to install python module with post-update hook
Plug 'skywind3000/vim-rt-format', { 'do': 'pip3 install autopep8' }

" By default, it will be triggered by `ENTER` in insert mode.
" set this to 1 to use `CTRL+ENTER` instead, and keep the  
" default `ENTER` behavior unchanged.
let g:rtf_ctrl_enter = 0

" Enable formatting when leaving insert mode
let g:rtf_on_insert_leave = 1
```

Enable plugin for current buffer:

```VimL
:RTFormatEnable
```

Then you go.

## Credit

TODO

