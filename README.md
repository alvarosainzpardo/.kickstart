# .kickstart
Kickstart config files for git and ssh

## Use

1. Install git (if not installed) and GNU stow
2. Clone this repo using https: `git clone https://github.com/alvarosainzpardo/.kickstart.git
3. Execute commands:

```bash
$ cd .kickstart
$ stow *
```

The above stow command creates symbolic links in the home directory for `~/.gitconfig`, `~/.gitignore`and `~/.ssh` folder.

4. Copy the files in the credentials archive folder to the `~/.ssh` folder
5. Clone the .dotfiles folder using ssh: `git clone git@github-alvarosainzpardo.com:alvarosainzpardo/.dotfiles.git`
6. Follow the instructions in the .dotfiles folder
