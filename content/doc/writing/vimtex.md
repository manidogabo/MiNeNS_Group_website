---
title: Writing in vim
linktitle: VimTeX
type: book
date: '2024-03-09'

icon: terminal
icon_pack: fas

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 3
---

{{% callout warning %}}
This page is still under construction!
{{% /callout %}}

Below, I document how I accomplish this in my terminal as my primary writing software on Mac.
I find this environment helps me to write faster and with less distraction than using other LaTeX IDEs. 

- Dependencies
    1. Iterm
    2. TeXLive
    2. Homebrew
- <span style="color:#F3B26D">**Steps**</span>
    1. Homebrew
        - install
        - add to path .zprofile
    2. NeoVim
        - install via Homebrew
        - install on Python3 `pip3 install pynvim`
    3. Install plugins from vim-plug
        - .local/nvim/init.vim
        - `:PlugInstall`
    4. Configure
        - .zshrc
        - .configure/neovim
- Other tools
    1. Ranger
        - .configure/ranger
    2. Overleaf
- Overleaf and Github workflow

{{% callout note %}}
{{< spoiler text="To-do" >}}
- [ ] flesh out the set-up instuctions
    - [ ] all the plugins
    - [ ] organization of output documents, figures, and other resources
{{< /spoiler >}}
{{% /callout %}}