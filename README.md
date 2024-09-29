<h1 align="center">😺 vim-kitty</h1>

<p align="center">
    <i>Vim and Neovim syntax highlighting for Kitty terminal config files.</i>
</p>

## 📜 Filetype detection

Any `*.conf` or `*.session` files in kitty's configuration directory is
considered.

You can always add `# vim:ft=kitty` at the beginning of any file to make sure
the syntax is loaded, or you can set it temporarily with `:set ft=kitty`.

## 🚀 Installation

### [lazy.nvim](https://lazy.folke.io/)

> [!IMPORTANT]
> Lazy.nvim only works in Neovim and is the recommended method for it.

```lua
{
    "warbacon/vim-kitty",
    ft = "kitty",
    tag = "*"  -- You can select a tagged version
}
```

### [vim-plug](https://github.com/junegunn/vim-plug)

> [!NOTE]
> Recommended method for Vim. Also works in Neovim but this is **Vimscript**.

```vim
" You can select a tagged version
Plug 'warbacon/vim-kitty', { 'tag': '*' }
```

## ❓ Extra

Keywords based on `v0.36.4`. The `gen-syntax.py` script syncs keywords with
your current Kitty version, check inside of it for instructions.

This is a fork of the [fladson plugin](https://github.com/fladson/vim-kitty)
which is intended to be always in sync with the latest version of Kitty and may
introduce some improvements in the future.
