### aviatrice - dotfiles
>A bunch of stuff to make life easier and better looking.

#### Installation
<ol>
    <li>Set your main projects directory <code>$PROJECT_DIR</code> in <code>lib/environment.d/dirs.sh</code> (default <code>$HOME/Projects</code>)</li>
    <li>Clone anywhere, set any variables with undesired defaults in <code>lib/environment.d</code></li>
</ol>

| LOC          | VAR                    | DESC                                                                                                        |
|--------------|------------------------|-------------------------------------------------------------------------------------------------------------|
| `dirs.sh`    | `$DOTFILES_REPO`       | `$PROJECT_DIR/dotfiles`                                                                                     |
| `dirs.sh`    | `$DOTFILES_DIR`        | `$HOME/.dotfiles`<br>If different from `$DOTFILES_REPO`, symlinked during install                           |
| `dirs.sh`    | `$DOTFILES_BACKUP_DIR` | `$HOME/.dotfiles.bak`                                                                                       |
| `install.sh` | `$SYMLINKS`            | maps paths from `$DOTFILES_REPO` to desired symlinks in `$HOME`<br>For files such as `.bashrc` and `.vimrc` |

<ol start=3>
    <li>Run <code>bin/install_dotfiles.sh</code> to install.</li>
</ol>
