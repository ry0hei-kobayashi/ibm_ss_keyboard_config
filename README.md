# IBM Space Saver Keyboard II TrackPoint Config

## 目的

IBM Space Saver Keyboard II の TrackPoint で，中央ボタンを押しながらスティックを動かしたときにスクロールできるようにする．

Linux では中央ボタン単体のクリックは中クリックとして扱われ，貼り付け動作になる．
この設定では，中央ボタンを押している間だけ TrackPoint の移動をスクロールとして扱う．

## セットアップ方法

本方法は，x11の場合有効である．
設定ファイルを `/etc/X11/xorg.conf.d/` に配置する．
