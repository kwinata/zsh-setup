# zsh-setup

## To use:

### First time only

Should clone this repo to home directory (`~/zsh-setup`)

Run the install script for the requirements
```
source ./install/oh-my-zsh
source ./install/bullet-train
source ./install/powerline
```

Install the configuration to your ~/.zshrc file by adding `source [PATH_TO_THIS_REPO]/entry_point` just before
```
source $ZSH/oh-my-zsh.sh
```

Then in your iterm, can set the font to `Meslo S for powerline`

### My common setup

- For g++-12 compiler, need `brew install gcc`
- Usually `brew install llvm` is better than macos built-in one. Can try to install. After installing, you will need to follow the configuration: `export PATH="/opt/homebrew/opt/llvm/bin:$PATH"`

### Config

Run `cp ./extra_config_example ./extra_config` and modify/add as needed.
