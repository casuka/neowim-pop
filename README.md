- sudo apt install neovim
- sudo apt install git
- sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
- nvim .config/nvim/init.vim
- :PlugInstall
Enjoy it...
