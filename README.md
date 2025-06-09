![preview](https://github.com/user-attachments/assets/a054d1d4-644d-43d2-84d0-6c5363f088f8)



## zsh-config
### My zsh configuration with powerlevel10k

This repository contains my .zshrc configuration, and the custom oh-my-zsh plugins to make it work. 

In order to make it work, the following dependencies are required:
- `lsd`
- `zsh`
- `oh-my-zsh`
- `vim`
- `powerlevel10k theme`
- `meslo nerd fonts`
- `tldr`

The powerlevel10k theme must be installed with oh-my-zsh, from https://github.com/romkatv/powerlevel10k

## Instructions/how to:
1. Install the dependencies by using yay/paru: `yay -S zsh oh-my-zsh vim lsd ttf-meslo-nerd-font-powerlevel10k tealdeer`
2. Set zsh as your default shell for your user, or for all users with `chsh -s $(which zsh)`
3. `git clone` this repository, and place the files on `$HOME/.oh-my-zsh/custom/plugins/`
4. Place this repo .zshrc file on $HOME (your home folder root). it will be hidden by default. overwrite if prompted by your system.
5. Run `p10k configure` to setup powerlevel10k to your liking.
6. Run `tldr -u` so it updates the tldr database.
7. Done. it should work as expected


### "but it doesn't work, help!"
open an issue tracker and I'll help you with it.
Let me know if I'm missing something to add to this readme, so this configuration works as expected.
You may refer to each dependency component docs for further info.
