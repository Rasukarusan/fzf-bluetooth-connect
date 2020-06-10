fzf-bluetooth-connect
====

![header]()

**Fuzzy search and connect to paired bluetooth device.**

## Description

You can connect to paired bluetooth device. This script use a apple script in shell script.

## Demo

![demo.gif]()

## Requirement

- fzf
- jq
- MacOS

## Install

### Homebrew

```bash
$ brew tap Rasukarusan/tap
$ brew install Rasukarusan/tap/fzf-bluetooth-connect
```

### Manually

```bash
$ git clone https://github.com/Rasukarusan/fzf-bluetooth-connect.git
```

## Usage

```bash
# homebrew
$ bluetooth-fzf

# manually
$ cd fzf-bluetooth-connect
$ ./bluetooth-fzf
```

I using a symple alias.
```bash
alias bll='bluetooth-fzf'
```


### Options
```bash
$ bluetooth-fzf --preview-window up # up / down / right /left
$ bluetooth-fzf --preview-window up:30%
$ bluetooth-fzf --no-preview
```

## Articles


## License

I'm lovin' fzf.

> The MIT License (MIT)
>
> Copyright (c) 2013-2020 Junegunn Choi

https://github.com/junegunn/fzf
