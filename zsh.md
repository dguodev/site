
## zsh-autosuggestions

https://github.com/zsh-users/zsh-autosuggestions

git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions 

## auto jump

```bash
git clone git@github.com:wting/autojump.git
cd autojump
./install.py
```

follow instruction , add 
```
[[ -s /home/mark/.autojump/etc/profile.d/autojump.sh ]] && source /home/mark/.autojump/etc/profile.d/autojump.sh
autoload -U compinit && compinit -u
```
into .zshrc
