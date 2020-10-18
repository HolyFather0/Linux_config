# Linux_config
It's my zsh and vim configs
1) Install zsh as default shell: ``` chsh -s $(which zsh) ``` and relog
2) Install Tilix ```sudo pacman -S tilix```
3) Install oh my zsh ```sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"```
4) Install p10k theme for ```zsh git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k```
5) Copy all config files to home dir
6) Install plugins for oh my zsh 
```
git clone https://github.com/zsh-users/zsh-completions ${ZSH_CUSTOM:=~/.oh-my-zsh/custom}/plugins/zsh-completions
git clone https://github.com/zsh-users/zsh-autosuggestions ~/.oh-my-zsh/custom/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ~/.oh-my-zsh/custom/plugins/zsh-syntax-highlighting
```
7) Install fzf ```git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf ~/.fzf/install```
8) ```source .zshrc```
