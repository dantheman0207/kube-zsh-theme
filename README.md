# kube-zsh-theme
An ohmyzsh theme, intended to work with Kubernetes.

![Kube Zsh Theme](https://github.com/dantheman0207/kube-zsh-theme/assets/1239724/4f0d2330-d3f9-46c9-a49d-00acf3ba5950)

This theme is my personal adaptation of `kube-zsh-theme` with some minor changes (adding namespace and some formatting).
- Tested on MacOS & WSL2

## Features
- shows the current time including seconds
- shows current kubectl context
- shows current kubectl namespace
- shows current dir
- shows current Git branch
- shows an arrow to differentiate input vs prompt
- uses different colors for readability

## Installation
1. Run in terminal: `git clone https://github.com/dantheman0207/kube-zsh-theme.git/ $ZSH_CUSTOM/themes/kube-zsh-theme`
1. Open your `.zshrc`
1. Change your `ZSH_THEME` to `kube-zsh-theme/kube`

## Format
`[CURRENT_TIME][⎈CURRENT_KUBECTL_CONTEXT:CURRENT_KUBECTL_NAMESPACE][CURRENT_DIR][GIT_PROMPT_INFO]➭$`
