# Modular tmux setup

0. `brew install tmux` or equivalent
1. Clone tpm: `git clone https://github.com/tmux-plugins/tpm ~/.config/tmux/plugins/tpm`
2. Create `~/.tmux.conf` with the following content:

```
source-file ~/.config/tmux/tmux.conf
```
3. Install plugins with tpm: `C-s I`
