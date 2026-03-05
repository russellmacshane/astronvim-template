# Russ Clone of AstroNvim Template

I've added a few tweaks to the default configuration that suite my needs and likes.

- Added TS, Prettier, and ESLint
- Added a Russ Bozo header override to the Dashboard
- Added a quit option to the Dashboard
- Added a Load Dirsession option to the Dashboard - I want to only load in the files that pertain to the folder I'm in.
- Added the Tokyonight color scheme
- Added `<Leader>ly` that yanks out a diagnostic message to easily send to claude
- Added `Leader>fy` that just yanks the relative file path to easily send to claude

# AstroNvim Template

**NOTE:** This is for AstroNvim v5+

A template for getting started with [AstroNvim](https://github.com/AstroNvim/AstroNvim)

## 🛠️ Installation

#### Make a backup of your current nvim and shared folder

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
mv ~/.local/state/nvim ~/.local/state/nvim.bak
mv ~/.cache/nvim ~/.cache/nvim.bak
```

#### Create a new user repository from this template

Press the "Use this template" button above to create a new repository to store your user configuration.

You can also just clone this repository directly if you do not want to track your user configuration in GitHub.

#### Clone the repository

```shell
git clone https://github.com/<your_user>/<your_repository> ~/.config/nvim
```

#### Start Neovim

```shell
nvim
```
