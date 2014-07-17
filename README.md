# Brant's dotfiles

Copied from [Paul's dotfiles](https://github.com/paulirish/dotfiles).

## private config

Toss it into a file called `.extra` which you do not commit to this repo and just keep in your `~/`

I do something nice with my `PATH` there:

```shell
# PATH like a bawss
export PATH=/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin
# ...

export PATH
```

## Syntax highlighting

…is really important. even for these files.

Install [Dotfiles Syntax Highlighting](https://sublime.wbond.net/packages/Dotfiles%20Syntax%20Highlighting) via [Sublime Text Package Control](https://sublime.wbond.net/installation)


## overview of files

####  Automatic config
* `.ackrc` - for ack (better than grep)
* `.vimrc`, `.vim` - vim config, obv.

#### shell environment
* `.aliases`
* `.bash_profile`
* `.bash_prompt`
* `.bashrc`
* `.exports`
* `.functions`
* `.extra` - not included, explained above

#### git, brah
* `.git`
* `.gitattributes`
* `.gitconfig`
* `.gitignore`

* `.inputrc` - config for bash readline

