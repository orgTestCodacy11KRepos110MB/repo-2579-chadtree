# CHADTree

Async File Manager for Neovim, Better than NERDTree.

## Features

### I like speed

- Incremental file system scan

- None blocking

- Literally every FS call is async.

### I like power

- Visual mode selections

- Copy, Paste, Delete, Rename, gotta do them all

![visual_select.gif](https://raw.githubusercontent.com/ms-jpq/chadtree/chad/preview/visual_select.gif)

- Quickfix integration

![quickfix.gif](https://raw.githubusercontent.com/ms-jpq/chadtree/chad/preview/quickfix.gif)

### I like colours

- Full `$LS_COLOR` support! (shows same colours as unix `ls` & `tree` commands)

![ls_colours.png](https://raw.githubusercontent.com/ms-jpq/chadtree/chad/preview/ls_colours.png)

- [Github coloured](https://github.com/github/linguist) icons

![github_colours.png](https://raw.githubusercontent.com/ms-jpq/chadtree/chad/preview/github_colours.png)

### I like version control

- Asynchronous parse git status (untracked, modified, staged)

![git.gif](https://raw.githubusercontent.com/ms-jpq/chadtree/chad/preview/git.png)

- Full support for git ignore, toggle show / hide

- Full support for globbing ignored files

### I like 21st century

- Follow mode

- Session support

- Full globbing support

- Ubiquitous locale-aware sorting

## Preview

## Install

Requires pyvim (as all python plugins do)

```sh
pip3 install pynvim
```

Install the usual way, ie. [VimPlug](https://github.com/junegunn/vim-plug), [Vundle](https://github.com/VundleVim/Vundle.vim), etc

```VimL
Plug 'ms-jpq/chadtree', {'branch': 'chad', 'do': ':UpdateRemotePlugins'}
```

## Documentation
