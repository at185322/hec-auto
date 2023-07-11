# HEC-AUTO

An auto setup script for HEC, with minimal config

## Config

open up `./hec`, and set the `HEC_PATH` variable to the path of where `hec-doc` is installed.

## Usage

`hec up` starts the docker container inside of hec-doc/dev-env
`hec down` stop the existing docker container

## Install

Drop this file anywhere in your path, or if you're feeling dangerous you can
run `sudo install hec /usr/bin/hec` (which hopefully should not work if NCR setup your mac correctly)

or, for bash

```bash
mkdir /Users/$(whoami)/bin
cp ./hec ~/bin/hec
echo 'PATH=$PATH:/Users/$(whoami)/bin' >> .bashrc
source ~/.bashrc
```

or, for zsh

```bash
mkdir /Users/$(whoami)/bin
cp ./hec ~/bin/hec
echo 'PATH=$PATH:/Users/$(whoami)/bin' >> .zshrc
source ~/.zshrc
```
