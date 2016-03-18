# banyan's dotfiles

## Installation
```zsh

# install zsh
sudo apt-get install zsh

# install oh-my-zsh
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

# http://blog.jobbole.com/41129/
sudo apt-get install fortune
sudo apt-get install cowsay

$ mkdir ~/git
$ git clone --recursive git://github.com/arvin-chou/config.git ~/git/config
$ cd ~/git/config
$ rake dotfiles:setup -v noop=true # run as dry-run
$ rake dotfiles:setup -v force=true

# install Vundle.vim.git
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/vundle/

# install antigen
source ~/.zsh.d/antigen/antigen.zsh
antigen theme banyan
antigen apply
```
