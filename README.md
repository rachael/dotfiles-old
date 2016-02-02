### aviatrice - dotfiles
>A bunch of stuff to make life easier and better looking.

#### Installation
Clone anywhere, set any variables with undesired defaults in `bin/install_dotfiles.sh`:
- `$source_repo` - default `$HOME/Projects/dotfiles`
- `$dotfiles_dir` - default `$HOME/.dotfiles` (symlinked to `$source_repo` during install)
- `$backup_dir` - default `$HOME/.dotfiles.bak`
- `$symlinks` - maps paths from `$source_repo` to desired symlinks in `$HOME`; for files such as `.bashrc` and `.vimrc`

Then run `bin/install_dotfiles.sh` to install.
