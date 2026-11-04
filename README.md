# tmux customizations

Byobu generates everything else in this directory. Only these files are mine:

- `.tmux.conf` turns the mouse on, makes `Ctrl+L` clear the screen and the scrollback, and replaces
  the right-click menu over shell output. The new menu adds Open Link and Copy Link, stays open after
  you release the button, and picks on a left click, as in Neovim and Emacs. Alt+right-click still
  shows tmux's full built-in menu.
- `tmux-url` finds the URL under the right-click and opens or copies it. The menu items call it.
- `tokyonight.tmux` loads the Tokyo Night tmux theme for the style in
  `~/.local/state/tokyonight/style` (`night` if the file is missing). The theme files come from
  Neovim's tokyonight.nvim plugin, so that plugin has to be installed.
