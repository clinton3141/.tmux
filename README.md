# Modular tmux setup

0. `brew install tmux` or equivalent
1. Clone repo: `git clone https://github.com/clinton3141/.tmux ~/.config/tmux/`
1. Clone tpm: `git clone https://github.com/tmux-plugins/tpm ~/.config/tmux/plugins/tpm`
3. Link config: `ln -s ~/.config/tmux/.tmux.conf ~/.tmux.conf`
4. Luanch tmux and install plugins with tpm: `C-s I`

## Keys

* Prefix: `C-s`
* Reload config: `C-s r`
* Pane navigation `C-s h/j/k/l` (vim)

## Plugin manager

[tmux-plugins/tpm](https://github.com/tmux-plugins/tpm)

## Theme

[catppuccin/tmux](https://github.com/catppuccin/tmux)
