# Trevors MacOS terminal Config!

Article with helpful info for reference: https://medium.com/@Clovis_app/configuration-of-a-beautiful-efficient-terminal-and-prompt-on-osx-in-7-minutes-827c29391961

# Quickstart


# Install brew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
- Read more: https://brew.sh/
- If you get: `zsh: command not found: brew`
    - https://stackoverflow.com/questions/36657321/after-installing-homebrew-i-get-zsh-command-not-found-brew


#  Install iterm 2
- https://iterm2.com/


#  To set custom theme for iterm 2...
-  https://iterm2colorschemes.com/
- I like this one [Apple Classic](https://raw.githubusercontent.com/mbadolato/iTerm2-Color-Schemes/master/schemes/Apple%20Classic.itermcolors)
- Copy the content into a file locally that called "AppleClassic.itermcolors"
- In iterm2 go to `settings > profiles > colors > color presets > import > select the file > click color presets > select the theme > Done!`
- Update the minimum contrast to 35. You'll thank me later! (In the same settings window)

# (Optional) Make iterm 2 transparent. trust me!
- go to settings
- go to profiles
- go to window
- set transparency. I like around 7.
- If you do this, you likely want to set blur as well. I set my blur to 15. This helps readability.

#  Install zsh and autocompletion
```
brew install zsh zsh-completions
``` 


# Install oh-my-zsh
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
Read more: https://ohmyz.sh/#install


#  Install auto sugestions and syntax highlighting to oh-my-zsh
```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```
#### NOTE: Depending on your theme, you may have issues with syntax highlighting. Please check the article above!

# Configure your `.zshrc` file
When you install oh-my-zsh, a config file is automatically generated. If you've installed the plugins I listed above, you'll want to edit the following places to ensure the theme and features are applied.
-  [Theme](https://github.com/trevorhauter/macos-config/blob/main/.zshrc#L11)
-  [Plugins](https://github.com/trevorhauter/macos-config/blob/main/.zshrc#L73)
-  [Brew](https://github.com/trevorhauter/macos-config/blob/main/.zshrc#L107)
-  [Aliases](https://github.com/trevorhauter/macos-config/blob/main/.zshrc#L111)
  
# Last but not least, you should toss the iterm2 guy a few bucks. It's a nice thing he's doing for the community.
    - https://iterm2.com/donate.html
