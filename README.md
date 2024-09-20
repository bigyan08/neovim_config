# Configuration of Plugin for neovim 

## Installation
1. Install neovim
    ```bash 
    sudo apt install neovim
2. Install vim-plugin manager from junes gunn
3. Go to .config directory and open a file init.vim 
    ```bash 
    cd ~/.config/
    nvim init.vim
4. Copy the content of init.vim 
5. Install packages npm and nodejs
    ```bash 
    sudo apt install npm
    sudo apt install nodejs
6. Go to coc.nvim file 
    ```bash
    cd ~/.local/share/nvim/plugged/coc.nvim
7. Then,
    ```bash
    npm ci
    npm run build
8. Open the file and type the command ":PlugInstall" and then ":CocInstall coc-pyright" for activating python autocompletion (similarly we can install autocompletions for other languages)
