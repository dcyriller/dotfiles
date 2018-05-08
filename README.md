# Clone .dotfiles

Clone dotfiles from github:
`git clone git@github.com:dcyriller/.dotfiles.git ~/.dotfiles --recurse-submodules`


# Use RCM

Install RCM from https://github.com/thoughtbot/rcm

Use it to symlink dotfiles from ~/.dotfiles to ~/.

`lsrc` will do a dry-run

`rcup -v -x README.md` will create the symlinks (verbose mode, excluding README
and gitconfig).

It symlinks zsh and shell config. Plus vim.


# Scripts

The scripts directory contains some installation scripts.

`ìnstall_homebrew` will install main packages after a fresh macOS install.
`install_js_packages` will install (globally) some usefull js packages.

These scripts should be sourced in PATH if RCM step was successfull.


# Setup git

Create a `.gitconfig.local` and set your email.
