# dotfiles
My list of dotfiles.
The list is managed using [chezmoi](https://www.chezmoi.io/quick-start/)

Programmes I am using include:

- Shell: [zsh](https://www.zsh.org/)
- Shell styling: [oh-my-posh](https://ohmyposh.dev/)
- Molecular Visualisation: PyMol, VMD

## Installation

Fist make sure you have installed all dependencies

```bash
sudo apt install git unzip zsh zsh-syntax-highlighting
```

Then these files can be installed and version controlled using

```bash
sh -c "$(curl -fsLS https://get.chezmoi.io)" --init --apply aretaon
```

If this does not work, you can still troublelshoot the underlying git:

```bash
chezmoi cd
git remote set-url "origin" https://github.com/aretaon/dotfiles.git
git branch --set-upstream-to=origin/main
git pull
```
