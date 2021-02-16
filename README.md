# RT-Format

Format current line immediately in INSERT mode as soon as you press ENTER:

![picture](https://github.com/skywind3000/images/raw/master/p/pep/rtformat_2.gif)

## Features

- Format current line in real-time when you press ENTER.
- No external process (eg. LSP servers) dependencies.
- Supported languages including: python, lua, ruby and javascript.

## Requirements

- Vim with "+python3" feature.
- Python module "autopep8".

## Quick Start

Install the plugin with vim-plug:

```VimL
Plug 'skywind3000/vim-rt-format'

" By default, it will be triggered by `ENTER` in insert mode.
" set this to 1 to use `CTRL+ENTER` instead, without changing 
" default `ENTER` behavior.
let g:rtf_ctrl_enter = 0

" Enable formatting when leaving insert mode
let g:rtf_on_insert_leave = 1
```

Prepare the "autopep8" module:

```bash
pip3 install autopep8
```

Enable plugin for current buffer:

```VimL
:RTFormatEnable
```

Then you go.

## Credit

TODO

