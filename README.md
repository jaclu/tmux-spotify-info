# tmux-spotify-info

Shows current song playing on spotify in your tmux statusline.

## My changes

limited max output length - the default sometimes completely filled the status line if one of the reported fields was really long.

Original can be found at [https://github.com/jdxcode/tmux-spotify-info](https://github.com/jdxcode/tmux-spotify-info)

## Dependencies
MacOS Only

## Install

### Installation with [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm) (recommended)

Add plugin to the list of TPM plugins in `.tmux.conf`:

    set -g @plugin 'jaclu/tmux-spotify-info'

Hit `prefix + I` to fetch the plugin and source it. That's it!

### Manual Installation

Clone the repository:

    $ git clone https://github.com/jaclu/tmux-spotify-info.git ~/clone/path



## Activation

Put `tmux-spotify-info` in your path.

Example: `ln -sf ~/.tmux/plugins/tmux-spotify-info/tmux-spotify-info ~/.local/bin`.

Add the following to status-right or status-left `#(tmux-spotify-info)`
