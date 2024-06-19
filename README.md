Trevors MacOS terminal Config!

Article with helpful info for reference: https://medium.com/@Clovis_app/configuration-of-a-beautiful-efficient-terminal-and-prompt-on-osx-in-7-minutes-827c29391961

Here's how you become cool like trev. If you get stuck or confused, please reference the article above.
- Install brew
    - https://brew.sh/ 
-  Install iterm 2
    -  https://iterm2.com/
    -  `brew cask install iterm2`
-  Install zsh and autocompletion
    - TODO: Isn't zsh already installed? Next time I set this up, see if we can drop the zsh install
    - `brew install zsh zsh-completions` 
- Install oh-my-zsh
    - https://ohmyz.sh/#install
    - Or just enter `su
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
-  Install auto sugestions and syntax highlighting to oh-my-zsh
    - Depending on your theme, you may have issues with syntax highlighting. Please check the article above!
    - `git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`
    - `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting`
