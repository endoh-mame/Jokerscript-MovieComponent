# Jokerscript-MovieComponent

## Overview

Jokerscriptで動画を再生するプラグイン

# Description

現在，MacOSX Sierra，Unity 5.4.0f3でのみ検証済み．
おそらくWindowsでは動くが，iOSとAndroidでは動かない．

現在，動画が自動で繰り返されてしまうバグの修正中です．
なので**スキップの設定はfalse**，**連続してmovieタグを使わない**ことを推奨します．

## Install

`Assets > Import Package > Custom Package...`

MovieJKS.unitypackageを選択

`JOKER_GAME/Resources`に再生したい動画ファイルを置く

## Usage

```
; 引数pathには拡張子抜きでファイル名
; skipはマウスクリックで動画をスキップする際はtrue，しない場合はfalse
[movie path="test" skip=true]
```

## TODO

- [ ] 再生時に動画が繰り返されるバグの修正

## Licence

MIT
