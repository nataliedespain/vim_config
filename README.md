# vim_config
Personal Vim Settings

# Getting Started
1. Install latest version of Vim with Homebrew

  ```brew update && brew doctor```

  ```brew install vim```

2. Clone repo into ~/.vim directory, usually created in the process of installation.

3. Copy .vimrc_backup into .vimrc and move into home path

  ```cp .vimrc_backup .vimrc && move .vimrc ~/.vimrc```

4. Create a directory to throw all your swapfiles in, b/c .vimrc

  ```mkdir ~/.vim/swapfiles```

5. Restart terminal to have changes take effect

## Don't forget fira-code &  ligatures


  ```brew tap caskroom/fonts```

  ```brew cask install font-fira-code```

Go change terminal settings, and Vim will autograb.

