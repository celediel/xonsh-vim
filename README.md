Xonsh syntax file from vim. Mostly stolen from python_vim and PRs are welcome!

### Install

#### The old school, manual way

```
git clone --depth 1 https://github.com/celediel/xonsh-vim ~/.vim
```

#### Or using your favourite plugin manager

#### neovim:

##### Packer

```lua
require('packer').startup(function()
    use {'celediel/xonsh-vim'}
end)
```

##### Paq

```lua
require "paq" {
    {'celediel/xonsh-vim'};
}
```
#### neovim or vim:

##### vim-plug

```vim
Plug 'celediel/xonsh-vim'
```

##### dein

```vim
call dein#add('celediel/xonsh-vim')
```
