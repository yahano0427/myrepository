# Calendar

https://qiita.com/ynakaDream/items/78c0c5ad9d1162de25f1
こいつを丸パクリ

Pod使い方手順
pod init
pod install(自分のmacにライブラリをinstallする必要があるため一度は必ず行う必要がある)

ライブラリを追加したい時
Podfileに追加したいライブラリを記載
pod install(1回目)
pod update(それ以降)

注意点
Calendar.xcworkspaceというファイルができるためそれを開かないとインストールしたライブラリが使えないみたい
なのでxcodeアプリからではなくFinderのCalender.xcworkspaceをクリックしてIDEを開く
