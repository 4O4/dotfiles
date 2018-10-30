# My dotfiles

These are my dotfiles for various machines. Some of them are carefully crafted by myself over the years, others are prepared by awesome people of the open source community and just slightly customized to suit my needs. Feel free to use them wherever and however you want. 

There's no dedicated documentation though, it's mostly just in my head except for external projects like .tmux and vimrc which are well documented by the authors (click on submodule dirs to quickly go to their repos).

Learn more about dotfiles in general here: https://dotfiles.github.io/

## How to

1. Get [yadm](https://thelocehiliosan.github.io/yadm/). Most portable way to do it:

```
mkdir -p $HOME/.local/bin && export PATH=$HOME/.local/bin:$PATH && curl -fLo $HOME/.local/bin/yadm https://github.com/TheLocehiliosan/yadm/raw/master/yadm && chmod a+x $HOME/.local/bin/yadm
```

2. Get the dotfiles

```
yadm clone https://github.com/4O4/dotfiles
```

3. Optionally adjust current CLASS in yadm and reload symlinks (learn more [here](https://thelocehiliosan.github.io/yadm/docs/alternates)

```
yadm config local.class work
yadm alt
```

4. Get zsh and Oh My ZSH for best experience on earth

```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
