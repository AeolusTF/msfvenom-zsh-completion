# msfvenom zsh completion  

![](https://i.imgur.com/DJV1Jie.gif)

## install 

```
# You have to install oh-my-zsh first.

# Download the msfvenom plugin.
git clone https://github.com/AeolusTF/msfvenom-zsh-completion ~/.oh-my-zsh/custom/plugins/msfvenom/

# Open your ~/.zshrc file and enable msfvenom plugin like below
# plugins=(git  msfvenom)

source ~/.zshrc
```

## bug
```
# Open the ~/.zshrc file and add it at the bottom, as shown below

fpath=(~/.zsh/completion $fpath)
autoload -Uz compinit && compinit -u
```

If you get stuck into troubles when using it, run `compinit` to reinitialize the zsh completion environment, reference [here](https://github.com/andsens/homeshick/issues/89).

