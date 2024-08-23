# Modular tmux setup

0. `brew install tmux` or equivalent
1. Clone tpm: `git clone https://github.com/tmux-plugins/tpm ~/.config/tmux/plugins/tpm`
2. Create `~/.tmux.conf` with the following content:

```
source-file ~/.config/tmux/tmux.conf
```
3. Install plugins with tpm: `C-s I`

## Keys

* Prefix: `C-s`
* Reload config: `C-s r`
* Window navigation `C-s h/j/k/l` (vim)

## Plugin manager

[tmux-plugins/tpm](https://github.com/tmux-plugins/tpm)

## Theme

[catppuccin/tmux](https://github.com/catppuccin/tmux)
