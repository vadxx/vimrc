# vimrc
The simple and fast Vim configuration for c/c++, python, php, html/css, javascript, java.
![demo]

## Installation
```bash
cd ~ && git clone https://github.com/vadxx/vimrc .vim && ln -s ~/.vim/vimrc ~/.vimrc
```
## Install Dependecies:

Ubuntu/Debian:
```bash
sudo apt-get install gcc git clang ctags python vim
```
macOS (install [homebrew] first):
```bash
brew install ctags python vim
```
### Optional:
For python style guide help:
```
pip install flake8
```
For markdown live server (install [node.js] first):
```
npm install -g livedown
```
You can use [live-server]:
```
npm install -g live-server
```

## Keybindings (custom)
For comfort, instead of `:` you can use `;`. 
### Base:
*   `SPC + q` - exit from window
*   `SPC + s` - save file
*   `SPC + t` - toggle NerdTree
*   `SPC + tf` - find file in NerdTree
*   `SPC + tb` - toggle TagBar
*   `SPC + f` - open fuzzy finder

To explore the standard features of Vim, I recommend pressing `F1`.

### Work with code:
*   `SPC + =` - auto format code
*   `SPC + c` - comment line(s)
*   `CTRL + e` - call Emmet
*   `CTRL + c` - copy text (global)
*   `CTRL + p` - paste text (global)
*   `<` and `>` - for indent line (or selected line)

### Window navigation:
*   `SPC + wt` - new tab
*   `SPC + wv` - split window vertical
*   `SPC + wh` - split window horizontal
*   `SPC + [1-9]` - go to that tab

### Extra:
*   `SPC + bg` - toggle light/dark theme
*   `SPC + ld` - togge Livedown-server

## Features
*   Simple modern config;
*   Minimal requirements (not needed other fonts, support vim7+ etc);
*   Syntax highlight;
*   Syntax checking error's and warnings;
*   Code completions;
*   Code auto formatter;
*   Snippets;
*   Easy keybindings;
*   Emmet;
*   Commender;
*   Clang support (deoplete-clangx);
*   Python support (Python-Jedi);
*   Java support (javacomplete2);
*   PHP support (phpcd);
*   File-tree navigation;
*   Tag-bar (needed ctags);
*   Fuzzy file finder;
*   Markdown live server;

## Contribute
### Fork me on GitHub
I'm always happy to take pull requests from others.

[homebrew]:https://brew.sh
[vim-plug]:https://github.com/junegunn/vim-plug
[Vim]:http://www.vim.org/download.php#pc
[node.js]:https://nodejs.org/en/
[live-server]:https://www.npmjs.com/package/live-server
[demo]:./demo.png

## License
MIT
