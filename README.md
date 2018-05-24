# 個人的な Karabiner の設定
- [Qiitaでの説明書き1](http://qiita.com/y-kishibata/items/444e192a9afdf6edd112)
- [Qiitaでの説明書き2](http://qiita.com/y-kishibata/items/2176c8dd1f9a41bb87dd)

## 注意点
- 基本的に下記を想定して記述しています
  - 英字キーボード利用
  - Windows → Mac に乗り換えた場合
  - Mac → Windows へリモートアクセス
- 一部、Seilを利用しています
- MacOS は El Captan を想定しています

## 主な変更
- リモートデスクトップ（＋Parallels）の設定を追加
  - MicrosoftのRDCを利用する場合のアプリ設定を追加
  - 右Commandを右Optionとして扱えるように対応
- 通常時にWindowsエミュレートの設定を追加
  - 左Command+\`（チルダ）で全角・半角切り替え
  - 右Command+\`（チルダ）で全角・半角切り替え
  - 左Option+\`（チルダ）で全角・半角切り替え
  - 右Option+\`（チルダ）で全角・半角切り替え
  - アプリケーションキーを右Commandとして対応
- Seilを利用してCapslockをF19として扱う
  - F19単体をCapslockとして対応
  - Shift+F19で全角・半角切り替え

## Elements用の追加設定
- For Japanese Windows Emuration（日本語環境向けの設定 Windowsエミュレート） (rev 1)
  - Shift＋Capslockを押した場合に英数・かなをtoggle方式にする
  - Command＋チルダを押した場合に英数・かなをtoggle方式にする
  - Command＋Escを押した場合に英数・かなをtoggle方式にする

### 注意点
- 配置先は ~/.config/karabiner/assets/complex_modifications
- ファイル名は数字.jsonなら問題ないようなので重複しないようにすること

## 変更履歴
- 2016.11.22 作成
- 2017.05.03 Capslockの制御を変更
- 2018.05.24 Elementsで利用する設定を追加
