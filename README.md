# VIM - The Archlinux Build
Vim feels like it requires one to have a degree in VimScript in order to use it for a proper workflow.
That changes now.
This repository is a mirror of the [Archlinux build](https://gitlab.archlinux.org/archlinux/packaging/packages/vim).

## Contents

The only different thing is the PKGBUILD as it allows for clipboard support and gets rid of the pesky GUI.
It also obviously contains the archlinux build of vim. Feel free to pull request to upload updates.
You can compile it on arch by cloning the repo and running makepkg like this

        git clone https://github.com/Burhan077/vim
        cd vim
        makepkg -si


hellpo
