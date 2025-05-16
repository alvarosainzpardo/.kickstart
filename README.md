# .kickstart
Kickstart config files for git and ssh

## Use

1. Install GNU stow
2. Clone this repo using https
3. Execute commands:

```bash
$ cd .kickstart
$ stow .
```

The above commands create symbolic links in the home directory for `~/.gitconfig`, `~/.gitignore`and `~/.ssh` folder.

4. Copy the files in the credentials archive folder to the `~/.ssh` folder
5. Clone the .dotfiles folder using ssh
6. Follow the instructions in the .dotfiles folder
