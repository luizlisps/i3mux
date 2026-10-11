# i3mux

An i3-inspired tmux pane configuration.

## Installation

Clone the repository:

```sh
git clone https://github.com/luizlisps/i3mux.git ~/.config/i3mux
```

Add this line to your `~/.tmux.conf`:

```tmux
source-file ~/.config/i3mux/tmux.conf
```

Reload tmux with `tmux source-file ~/.tmux.conf`, or start a new session. Key bindings are documented at the top of `tmux.conf`.

The top bar shows numbered tmux windows, highlights the focused window,
and indicates active tiling or resize mode. Command prompts fill the bar
instead of overlapping the window list. No Git, shell prompt, clock, or
system-theme integration is required.

## License

Apache-2.0. See [LICENSE](LICENSE).
