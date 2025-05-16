# .kickstart
Kickstart config files for git and ssh

## Use

1. Install git (if not installed) and GNU stow
2. Clone repo:

```bash
git clone https://github.com/alvarosainzpardo/.kickstart.git
```

```bash
cd .kickstart
```
3. Create symbolic links in the home directory for `~/.gitconfig`, `~/.gitignore`and the `~/.ssh` folder:

```bash
cd .kickstart
stow git ssh
cd
```
3. Copy the files in the credentials archive folder to the `~/.ssh` folder
4. Clone the .dotfiles folder using ssh: `git clone git@github-alvarosainzpardo.com:alvarosainzpardo/.dotfiles.git`
5. Follow the instructions in the .dotfiles folder
