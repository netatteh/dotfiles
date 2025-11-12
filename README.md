# dotfiles
Configuration files for local Linux / MACOS environments.

## Usage
1. Install GNU `stow` with your package manager
```bash
# Debian Linux with apt
sudo apt install stow

# MACOS
brew install stow
```
2. Clone this repository to your *$HOME* directory
```bash
cd $HOME
git clone git@github.com:netatteh/dotfiles.git
```
3. Run `stow <application_folder> --adopt` for all the configuration folders you wish to introduce to the new system
4. If any of the dotfiles already exist, stow will copy the existing files over to `$HOME/dotfiles` and git will show them as changes in working directory. If you want to keep the files in this repository, reset any changes with `git restore`.
```bash
cd $HOME/dotfiles
git restore .
```

