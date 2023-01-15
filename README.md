# Iceberg Neovim

My personal fork of Oscar (oahlen) Ahlén [iceberg.nvim](https://codeberg.org/oahlen/iceberg.nvim).

___


Lua colorscheme inspired from [iceberg.vim](https://github.com/cocopon/iceberg.vim)

All credits go to Hiroki Kokubun [cocopon](https://github.com/cocopon) for creating the awesome theme in the first place!

## Installation 

With [packer.nvim](https://github.com/wbthomason/packer.nvim)

```lua
use "harg/iceberg.nvim"
```

## Usage

Enable the colorscheme:
```lua
vim.cmd.colorscheme("iceberg")
```
Enable the colorscheme in your lualine config:
```lua
require('lualine').setup {
  options = {
    -- ... your lualine config
    theme = 'iceberg'
    -- ... your lualine config
  }
}
```
