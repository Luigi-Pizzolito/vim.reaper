<p align="center">
  <img src="https://gideonwolfe.com/img/neovim/reaper/ascii.png" width="600" height="400" title="vim.reaper">
</p>
   
<p align="center">💀 A Hackable, Fully Featured, Rice Friendly Neovim Configuration 💀</p>

# Features

* 🎨 Colorscheme generated with [pywal](https://github.com/dylanaraps/pywal)
* 💭 Intellisense, Completion, and Linting with [coc.nvim](https://github.com/neoclide/coc.nvim)
* 🏷️ Tag management with [vista.vim](https://github.com/liuchengxu/vista.vim)
* 🔀 Git integration with [vim-fugitive](https://github.com/tpope/vim-fugitive) and [vim-gitgutter](https://github.com/airblade/vim-gitgutter)
* ✈️ Informative statusline and tabline with [vim-airline](https://github.com/vim-airline/vim-airline)
* ✂️ Code snippets powered by [UltiSnips](https://github.com/sirver/UltiSnips)
* 💡 Intelligent suggestions with [vim-tabnine](https://github.com/zxqfl/tabnine-vim)
* 📁 Simple file browsing with [NERDTree](https://github.com/scrooloose/nerdtree)
* 📜 Dynamic homepage with [vim-startify](https://github.com/mhinz/vim-startify)

# Installation

Currently you can simply copy `init.vim` into your neovim config directory. However I am planning to break up the main config file into more modular, manageable parts. Stay tuned.

# Usage

## Basic Usage

* To quickly switch from `INSERT` to `NORMAL` mode, press `jk` or `kj` quickly.
* In `NORMAL` mode, press `TAB` or `Shift+TAB` to cycle through open buffers.
* `<Leader>` has been mapped to `SPACE`. In general, functions related to certain plugins can be started with the first letter of the plugin. For example: `<Leader>c` would be the root of commands relating to `CoC`.

## Startify
To open Neovim to the startify buffer, simply launch `nvim` without any arguments. Your recently edited files will be displayed, as well as recently edited files from the current directory.
<p align="center">
  <img src="https://gideonwolfe.com/img/neovim/reaper/startify.png" width="640" height="360" title="startify">
</p>

## Completion
In the middle of a word, you can press `TAB` to open the Coc floating completion menu. This menu should be populated with sippets from `UltiSnips`, smart complete from `TabNine`, and any other completion suggestions. Press `Shift+Tab` to go up in the menu, and `Enter` to select an option.
<p align="center">
  <img src="https://gideonwolfe.com/img/neovim/reaper/completion.png" width="640" height="360" title="startify">
</p>
Note: Windows are set to the background color because the other colors look gross IMO. Ideally we could have a border on the floating windows but that is not implemented in CoC yet.

## NERDTree
In any buffer, press `F7` to open the NERDTree file browser. Optionally disable the `nerdtree-highlights` plugin if you don't want syntax highlighting in NT. 
<p align="center">
  <img src="https://gideonwolfe.com/img/neovim/reaper/nerdtree.png" width="640" height="360" title="startify">
</p>

## Airline
### Tabline
The tabline will display the currently open buffers, and wheather they have been modified.
<p align="center">
  <img src="https://gideonwolfe.com/img/neovim/reaper/tabline.png" width="740" height="13" title="startify">
</p>

### Statusline
The status line displays 
<p align="center">
  <img src="https://gideonwolfe.com/img/neovim/reaper/statusbar.png" width="740" height="13" title="startify">
</p>
