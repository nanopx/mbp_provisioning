# macbookpro_provisioning

## インストールメモ

- XCodeインストール(Mac App Store)

- XCode license同意
```bash
sudo xcodebuild -license
```

- Xcode CommandLineToolインストール
```bash
xcode-select --install
```

- Homebrewインストール
```bash
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

- brew環境整備
```bash
brew doctor
```
```bash
brew update
```

- Ansibleインストール
```bash
brew install python
```
```bash
brew install ansible
```

- このリポジトリをclone

- 環境構築
```bash
HOMEBREW_CASK_OPTS="--appdir=/Applications" ansible-playbook -i hosts -vv localhost.yml
```
```bash
homesick clone nanopx/dotfiles
```
```bash
homesick symlink dotfiles
```

- Caskの一時データなどを削除
```bash
brew cask cleanup
```
