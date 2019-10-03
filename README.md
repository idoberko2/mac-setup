# Terminal
1. Install [iTerm2](https://www.iterm2.com/)
2. Install [Homebrew](https://brew.sh/) by executing `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
    1. If an xcode error occurs, execute `xcode-select --install`
3. Install `zsh` by executing `brew install zsh`
4. Change shell to `zsh` by running `chsh -s /usr/local/bin/zsh`
5. Install [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) by executing `sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
6. Install [pure](https://github.com/sindresorhus/pure)
7. Install syntax highlighting plugin by executing `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting`
8. Install autosuggestion pluging by executing `git clone https://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions`
9. Import iTerm2 profiles by following [these instructions](https://stackoverflow.com/a/56821180/4980768)
10. Execute `cp ./.zshrc ~/.zshrc`

Based on [this article](https://www.freecodecamp.org/news/jazz-up-your-zsh-terminal-in-seven-steps-a-visual-guide-e81a8fd59a38/)


# Apps
## VS Code
Execute `cp ./vscode_settings.json $HOME/Library/Application\ Support/Code/User/settings.json`