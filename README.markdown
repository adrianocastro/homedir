# Home directory

This is my basic homedir setup which includes config files and some binaries.

I keep it under revision control so it's easier to setup new machines and keep existing ones in sync.

This approach draws inspiration from [Mark Norman Francis](https://github.com/norm/)' [home](https://github.com/norm/home/) and [homedir](https://github.com/norm/homedir/) setup.

The structure attempts to:

1. Keep everything inside a single revision controlled folder (`homedir`)
1. Loosely nimic the Unix file system hierarchy inside that folder (configurations in `etc`, binaries in `bin`, etc)
1. Keep things separate and clear
1. Avoid hidden files

This is highly personal and may or may not work for you but feel free to clone or fork my work in you think it's useful.

## Usage and installation

1. back up all your config files (e.g. .bashrc, .bash_profile, .vimrc, .gitconfig, etc)
1. clone this repository
1. manually create symlinks to the files in homedir/etc
