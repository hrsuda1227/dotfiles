# dotfiles

```bash

echo "# dotfiles" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/hrsuda1227/dotfiles.git
git push -u origin main

…or push an existing repository from the command line
git remote add origin https://github.com/hrsuda1227/dotfiles.git
git branch -M main
git push -u origin main


```

## stow setup

```bash

brew install stow

git clone  https://github.com/hrsuda1227/dotfiles.git

cd dotfiles

stow nvim zsh alacritty kitty lazygit  scripts tmux wezterm hammmerspoon

dotfileがルートと.config配下にリンクが貼られる
```
