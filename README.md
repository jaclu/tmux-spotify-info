# My changes

limited max output length - the default sometimes completely filled the status line if one of the reported fields were really long


tmux-spotify-info
=================

Shows current song playing on spotify in your tmux statusline. OSX only.

Installation
============

Put `tmux-spotify-info` in your path. I suggest `~/bin`.

Add the following to `~/.tmux.conf`

```
set -g status-right '#(tmux-spotify-info)'
```

Or for a more complete statusline like [the one I have](https://github.com/dickeyxxx/dotfiles/blob/master/tmux.conf)

Other Tmux Plugins
==================

* [tmux-cpu-info](https://github.com/dickeyxxx/tmux-cpu-info)
* [tmux-weather](https://github.com/dickeyxxx/tmux-weather)
