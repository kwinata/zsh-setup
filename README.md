# zsh-setup

## To use:
Clone this repository to your home directory
```
cd ~
git clone https://github.com/kwinata/zsh-setup
```

### First time only
Run the install script for the requirements
```
source ~/zsh-setup/install/oh-my-zsh
source ~/zsh-setup/install/bullet-train
source ~/zsh-setup/install/powerline
```

Install the configuration to your ~/.zshrc file by adding `source ~/zsh-setup/entry_point` just before the line
```
source $ZSH/oh-my-zsh.sh
```

Then in your iterm, set the fonts to `Meslo S for powerline`

### Tips

- For g++-12 compiler, need `brew install gcc`
- Usually `brew install llvm` is better than macos built-in one. Can try to install. After installing, you will need to follow the configuration: `export PATH="/opt/homebrew/opt/llvm/bin:$PATH"`