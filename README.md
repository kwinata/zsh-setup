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

Then in iterm (if using iterm), can set the font to `Meslo S for powerline`

Run `cp ./extra_config_example ./extra_config` and modify/add as needed.

## Note about cpp

Reminder to self to not need to install cpp compiler in mac for competitive programming questions because it's too troublesome.
Just use docker like this:

```bash
docker run -it -v "$(pwd):/code" gcc:12 bash 
```

