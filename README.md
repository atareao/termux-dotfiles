# TERMUX DOTFILES

Dotfiles of my Termux configuaration.

### Installed

Configure acceso a resto de la unidad
```bash
termux-setup-storage
```

Configure `fish` as your shell. If you don't want to use this shell, don't run following commands.

```bash
pkg install fish
chsh -s fish
```

Install awesome software,

```bash
pkg install lsd git bat lsd starship pass neovim atuin zoxide make \
            ripgrep yadm nodejs libllvm clang yazi lazygit zellij
```

Clone the termux doftiles repository with the configuration

```bash
cd ~
git clone https://github.com/atareao/termux-dotfiles.git .
```

If you have `password-store` clone it from your repo.

```bash
git clone git@github.com/atareao/tomb.git ~/.password-store
```

Otherwise I recomend create your password store. In order to do that

