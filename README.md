### aviatrice - dotfiles
>A bunch of stuff to make life easier and better looking.

#### Installation
<ol>
    <li>Set your main projects directory in <code>lib/environment.d/dirs.sh / $PROJECT_DIR</code></li>
    <li>Clone anywhere, set any variables with undesired defaults in <code>lib/environment.d</code></li>
</ol>

| LOC          | VAR                    | DESC                                                                                                                         |
|--------------|------------------------|------------------------------------------------------------------------------------------------------------------------------|
| `dirs.sh`    | `$DOTFILES_REPO`       | `$PROJECT_DIR/dotfiles`                                                                                                      |
| `dirs.sh`    | `$DOTFILES_DIR`        | `$HOME/.dotfiles`; maps paths from `$DOTFILES_REPO` to desired symlinks in `$HOME`; for files such as `.bashrc` and `.vimrc` |
| `dirs.sh`    | `$DOTFILES_BACKUP_DIR` | `$HOME/.dotfiles.bak`                                                                                                        |
| `install.sh` | `$SYMLINKS`            | maps paths from `$DOTFILES_REPO` to desired symlinks in `$HOME`; for files such as `.bashrc` and `.vimrc`                    |

<ol start=3>
    <li>Run `bin/install_dotfiles.sh` to install.</li>
</ol>
