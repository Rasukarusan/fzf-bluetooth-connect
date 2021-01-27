fzf-bluetooth-connect
====

<img src="https://user-images.githubusercontent.com/17779386/84265517-eaee1080-ab5d-11ea-80c8-da41554ccfbf.png" width="600">

**Fuzzy search and connect to paired bluetooth device.**

## Description

You can connect to paired bluetooth device. This script use a apple script in shell script.

## Demo

<img src="https://user-images.githubusercontent.com/17779386/97555696-c1098d80-1a1b-11eb-8646-30e2999d5a94.gif" width="600">

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

https://www.rasukarusan.com/entry/2020/06/10/214750

## License

MIT
