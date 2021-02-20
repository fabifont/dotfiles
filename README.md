# Personal dotfiles

## Alacritty
`cp alacritty/alacritty.yml ~/.config/alacritty/alacritty.yml`

## Zsh
1. Install `zsh`
2. Change default shell: `chsh -s $(which zsh)`
3. Install `oh-my-zsh`: `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
4. Install plugins:
    - `zsh-completions`: `git clone https://github.com/zsh-users/zsh-completions ${ZSH_CUSTOM:=~/.oh-my-zsh/custom}/plugins/zsh-completions`
    - `zsh-autosuggestions`: `git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`
    - `zsh-syntax-highlighting`: `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting`
    - `zsh-history-substring-search`: `git clone https://github.com/zsh-users/zsh-history-substring-search ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-history-substring-search`
5. Copy dotfiles: `cp zsh/.zshrc ~/.zshrc; cp zsh/.p10k.zsh ~/.p10k.zsh`