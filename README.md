# IBM Space Saver Keyboard II TrackPoint Config

## 目的

IBM Space Saver Keyboard II の TrackPoint で，中央ボタンを押しながらスティックを動かしたときにスクロールできるようにする．

Darwin/Mac では中央ボタン単体のクリックは中クリックとして扱われ，貼り付け動作になる．
この設定では，中央ボタンを押している間だけ TrackPoint の移動をスクロールとして扱う．
ソフトウェアはkarabinerを使用する．

## セットアップ方法

設定ファイルを配置する．
```
cp ibm-space-saver-trackpoint-mac.json ~/.config/karabiner/assets/complex_modifications/ibm-space-saver-trackpoint-mac.json
```

karabinerのcomplex_modificationsメニューから追加し，enableにする．
