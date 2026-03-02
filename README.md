1. Clone this repo into $HOME
2. cd into this repo
3. Create `git/.gitconfig.local` with:
   ```
   [user]
           signingkey = <path to .pub key>
   ```
4. run `stow git` to create symlinks in $HOME to all files in git folder


Note: README.* files are ignored by default by stow
