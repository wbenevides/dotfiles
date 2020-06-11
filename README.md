# dotfiles
Dotfiles. Designed to be managed with GNU Stow

## Usage Instructions
1. Download the repository into **HOME FOLDER** (this step is important because the way `gnu-stow` works!)
```sh
git clone git@github.com:wbenevides/dotfiles.git $HOME
```
2. Change to dir
```bash
cd $HOME/dotfiles
```
3. How to execute the scripts?
* Navigate to the folder $HOME/dotfiles and run `./startup.sh`
  * If there is a permission error, run `chmod +x startup.sh` or `/bin/sh startup.sh`
4. Install what you want with gnu-stow, like
```bash
stow bash
stow vim
```
