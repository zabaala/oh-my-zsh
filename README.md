# oh-my-zsh
oh-my-zsh configuration

##Instalation

### Install Iterm2
```bash
$ brew cask install iterm2
```

### Install Oh My ZSH
```bash
$ sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
### Configuring your ~/.zshrc
1. Define the theme `ZSH_THEME="agnoster"` and default user `DEFAULT_USER=yourusername`. 
2. [DOwnload Solarized Color Scheme](http://ethanschoonover.com/solarized) and exteact files. 
3. Open iTerm2 and goto `Preferences (Cmd+,) > Profile > Colors > Colors Presets > Import...` and select `Solarized Dark.itermcolors` file inside of `iterm2-colors-solarized` folder. TIP: If you prefer you can set a more clear color to Foreground basic color. Foreground color refer to text color.
4. [Download or clone patched fonts from Vim-Powerline](https://github.com/powerline/fonts). 
5. After download, create a Collection named "Meslo" and move Meslo fonts to inside of this collection.
6. Open iTerm2 preferences, goto `Profile > text > Font > Change Font` and click in Meslo Collection and Select "Meslo LG L for powerline" family, after select a regular typeface, define font size and adjust vertical/horizontal character spacing.

On the end of these processes, the appearance of your iterm2 must be like this:
![alt text](https://github.com/zabaala/oh-my-zsh/blob/master/my-iterm2-appearence.png "Customized iTerm2 appearence")
