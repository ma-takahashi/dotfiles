# dotfiles

## .gitconfig

    ln -nfs {project_root}/.gitconfig .gitconfig



## Brewfile

### 確認

    brew bundle check --file=brew/Brewfile --verbose

### インストール

    brew bundle --file=brew/Brewfile
