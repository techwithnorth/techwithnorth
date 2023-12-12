#Bash aliases _(ver.2)_

The nice approach is move all of your's aliases to separate folder. You can do it by adding the following line to .bashrc

    . ~/.aliases

Open yours .aliases and add a desired alias by the following:

    alias <alias_name>=<'command that you wish to bind>

Here's some ideas based on that what I use daily

\### LS (exa is a better version of ls)

    alias ls='exa --color=auto --icons'
    alias ll='exa -l --icons'
    alias lll='exa -l | less'
    alias l='ls -lav --ignore=.?*'

\### Text edit

    alias nano='micro' #micro is a nano on a steroids, more eye pleasing but still easy to use
    alias v='nvim'
    alias vi='nvim'
    alias vim='nvim'

\### directories
    alias cddoc='cd ~/Documents'
    alias cdd='cd ~/Documents/Download'

\### system
    alias s='sudo'
