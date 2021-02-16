# RT-Format

Format current line immediately in INSERT mode as soon as you press ENTER:

![picture](https://github.com/skywind3000/images/raw/master/p/pep/rtformat_2.gif)

## Features

- Format current line in real-time when you press ENTER.
- No external process (eg. LSP servers) is needed.
- Supported languages including: python, lua and javascript.

## Requirements

- Vim with "+python3" feature.
- Python module "autopep8".

## Quick Start

Install the plugin with vim-plug:

```VimL
Plug 'skywind3000/vim-rt-format'
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

