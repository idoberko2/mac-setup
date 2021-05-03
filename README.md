# Terminal
1. Install [iTerm2](https://www.iterm2.com/)
1. Install [Homebrew](https://brew.sh/) by executing `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
    1. If an xcode error occurs, execute `xcode-select --install`
1. Install [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) by executing `sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
1. Install [pure](https://github.com/sindresorhus/pure)
1. Install syntax highlighting plugin by executing `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting`
1. Install autosuggestion plugin by executing `git clone https://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions`
1. Install git-prune plugin by executing `git clone https://github.com/diazod/git-prune $ZSH_CUSTOM/plugins/git-prune`
1. Install [Fira Code font package](https://github.com/tonsky/FiraCode/wiki/Installing)
1. Import iTerm2 profiles by navigating to Settings > Profiles > Import from JSON... or if that didn't work, following [these instructions](https://stackoverflow.com/a/56821180/4980768)
1. Execute `cp ./.zshrc ~/.zshrc`

Based on [this article](https://www.freecodecamp.org/news/jazz-up-your-zsh-terminal-in-seven-steps-a-visual-guide-e81a8fd59a38/)


# Apps
## VS Code
Execute `cp ./vscode_settings.json $HOME/Library/Application\ Support/Code/User/settings.json`