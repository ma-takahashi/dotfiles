# dotfiles

## .gitconfig

    ln -nfs {project_root}/.gitconfig .gitconfig



## Brewfile

### 事前準備

    brew install argon/mas/mas
    brew install rcmdnk/file/brew-file


### シンボリックリンク

    cd ~/.brewfile
    ln -nfs {project_root}/brew/Brewfile Brewfile


### インストール

    brew file install
