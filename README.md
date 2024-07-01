Trevors MacOS terminal Config!

Article with helpful info for reference: https://medium.com/@Clovis_app/configuration-of-a-beautiful-efficient-terminal-and-prompt-on-osx-in-7-minutes-827c29391961

Here's how you become cool like trev. If you get stuck or confused, please refer to the article above.
- Install brew
    - `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"` 
        - Read more at https://brew.sh/
        - Tip: If you see `zsh: command not found: brew` Go here https://stackoverflow.com/questions/36657321/after-installing-homebrew-i-get-zsh-command-not-found-brew

-  Install iterm 2
    - Read more at https://iterm2.com/
-  To set custom theme for iterm 2...
    -  https://iterm2colorschemes.com/
    - I like this one (AppleSystemColors)https://raw.githubusercontent.com/mbadolato/iTerm2-Color-Schemes/master/schemes/Apple%20System%20Colors.itermcolors
    - Copy the content into a file locally that called "AppleSystemColors.itermcolors"
    - In iterm2 go to settings > profiles > colors > color presets > import > select the file > click color presets > select the theme > Done!
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
- Last but not least, you should toss the iterm2 guy a few bucks. It's a nice thing he's doing for the community.
    - https://iterm2.com/donate.html
