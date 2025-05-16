# .kickstart
Kickstart config files for git and ssh

## Use

1. Install git and GNU stow (if not installed)
2. Clone repo:

```bash
cd
git clone https://github.com/alvarosainzpardo/.kickstart.git
```

3. Create symbolic links in the home directory for `~/.gitconfig`, `~/.gitignore`and the `~/.ssh` folder:

```bash
cd ~/.kickstart
stow git ssh
cd
```

4. Copy the files in the credentials archive folder to the `~/.ssh` folder
