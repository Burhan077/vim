# VIM - The Archlinux Build
Vim feels like it requires one to have a degree in VimScript in order to use it for a proper workflow.
That changes now.
This repository is a mirror of the [Archlinux build](https://gitlab.archlinux.org/archlinux/packaging/packages/vim).

## Compiling

The only different thing is the PKGBUILD as it allows for clipboard support and gets rid of the pesky GUI.
It also obviously contains the archlinux build of vim. Feel free to pull request to upload updates.
You can compile it on arch by cloning the repo and running makepkg like this

        git clone https://github.com/Burhan077/vim.git
        cd vim
        makepkg -si

This allows for clipboard support. Now you can use these [dotfiles](https://github.com/Burhan077/Dotfiles.git) to make use easier. 
Make sure to actually read the .vimrc so that you can know what's going on.
Also install the plugins using the pluginstall command in vim's command mode 

        PlugInstall 

Another vim easy mode is by running vim with the y option like this

        vim -y
        
>[!NOTE]
>
>This is not an official mirror.
>
>I have edited the PKGBUILD so please make sure to read it.
>
>This repo is meant to help people use vim with friendly keybindings.
>
>It's also meant to make workflow more streamlined while using vim.
>

