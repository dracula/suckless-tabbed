### [Suckless Tabbed](https://tools.suckless.org/tabbed/)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    git clone https://github.com/dracula/tabbed.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/tabbed/archive/master.zip) option and unzip them.

#### Activating theme

1. `cd` into the tabbed source directory
2. If you don't have a `config.h` file: run `make` to compile the source code
3. Run `git apply <path of this repo>/theme.patch` (you might have to add `--3way` if the line numbers changed)
4. Recompile & Reinstall
5. Boom! It's working (you might have to restart running instances of tabbed)
