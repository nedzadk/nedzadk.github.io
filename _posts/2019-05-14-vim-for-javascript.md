---
layout: post
title: Vim configuration for JavaScript
tags:
  - javascript
  - vim
  - react
  - node
---

![VimConfig](/images/posts/vim_config.jpg)

This is my Vim configuration that works perfect with modern JS frameworks/libraries. 

It includes:

- NERDTree (for file navigation)
- Ale (for eslinting) 
- Prettier (for code formatting) 
- COC (for IntelliSense autocompletion) 
- different JS, JSX libraries to support modern JS syntax highlighting 
- ...and some other plugins, for more details see [here](https://github.com/nedzadk/dotfiles)

One more image showing Linter and Prettier in action

![VimConfig](/images/posts/vim_config2.jpg)


My dotfiles can be found [here](https://github.com/nedzadk/dotfiles)! 

```
Requirements:
curl is required to run setup_vim.sh (ubuntu: sudo apt install curl)
You need to have `node` and `npm` installed before running `:PlugInstall`
```
Setup process
- clone the repo 
- run `setup_vim.sh` inside cloned repo directory (this will backup your existing vim configuration)
- open Vim and run `:PlugInstall`
- and you should be good to go

**Info:** This is only tested on Ubuntu 18.04+
