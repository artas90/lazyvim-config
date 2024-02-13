Install config
```bash
  git clone --depth 1 https://github.com/artas90/lazyvim-config.git ~/.config/nvim
```

Uninstall config
```bash
  rm -rf ~/.config/nvim && \
  rm -rf ~/.local/share/nvim && \
  rm -rf ~/.cache/nvim
```

with sudo
```bash
  sudo rm -rf ~/.config/nvim && \
  sudo rm -rf ~/.local/share/nvim && \
  sudo rm -rf ~/.cache/nvim
```

Misc
```bash
  sudo mkdir -p ~/.config && sudo chown `whoami`:`whoami` ~/.config
```
