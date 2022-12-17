doas-zsh
===
This is a fork of [Oh-my-zsh's sudo plugin](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/sudo)

prefix your current or previous commands with ```doas``` by pressing <kbd>Ctrl+s</kbd> twice

installation
---
```
git clone --depth 1 [repo] ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-doas
echo 'source $ZSH/custom/plugins/zsh-doas/doas.zsh' >> ${ZDOTDIR:-$HOME}/.zshrc
```
