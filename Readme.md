# 自分用Mac用Dotfile
- 自分用のMacのDotfile。
- 個人的に必要な物の寄せ集め。
- 個人用なので設定ミス等含まれる可能性あり。使用する場合は注意。

## 日本語のディレクトリ名を英語へ変更
```
rm ~/Applications/.localized
rm ~/Documents/.localized
rm ~/Downloads/.localized
rm ~/Desktop/.localized
rm ~/Public/.localized
rm ~/Pictures/.localized
rm ~/Music/.localized
rm ~/Movies/.localized
rm ~/Library/.localized
```
もしくは
```
find . -name .localized
find . -name .localized -delete
find . -name .localized
```

## Homebrewインストール
- 何が無くともここから始めないと何も出来ない。
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

```
cd
git clone https://github.com/xxakatukixx/dotfiles.git
cd ~/dotfiles
./homebrew.sh
```

以下タスク。工事中。
## zshの設定を考える

## GUI側の設定