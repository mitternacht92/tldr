# Manuals are too Long and Life is too Short

## Bash Foreground Colors

```bash
FG_0="\[\033[38;5;0m\]"  # BLACK
FG_1="\[\033[38;5;1m\]"  # RED
FG_2="\[\033[38;5;2m\]"  # GREEN
FG_3="\[\033[38;5;3m\]"  # YELLOW
FG_4="\[\033[38;5;4m\]"  # BLUE
FG_5="\[\033[38;5;5m\]"  # MAGENTA
FG_6="\[\033[38;5;6m\]"  # CYAN
FG_7="\[\033[38;5;7m\]"  # WHITE
FG_8="\[\033[38;5;8m\]"  # GREY
```

## [Unlimited Bash History](https://stackoverflow.com/questions/9457233/unlimited-bash-history)

```bash
export HISTSIZE=-1
export HISTFILESIZE=-1
```

## Generate Unix Time (Epoch) string

`date '+%s'`

## Convert Unit Time (Epoch) to Datetime Stamp

`date -d @12345679`

## [list terminal escape key codes](https://superuser.com/questions/269464/understanding-control-characters-in-inputrc)

`infocmp -L -1`

## List Tmux Sessions

`tmux list-sessions`

## Re-attach to a Tmux Session

`tmux attach -d -t`

## List all processes in tree-like format

`ps aux --forest`

## List the size of current path

`du -hs * | sort -hr`

## Copy text to X11 Clipboard

`xclip -sel clip "hello world!"`

## Look up a term with regex recursively

`grep -r /path/to/folder -e "hello world!"`
