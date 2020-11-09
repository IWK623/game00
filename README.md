# Simple スネーク
https://phaser.io
Phaserのサンプルの１つです。

## 遊び方
キーボードの移動キーでスネークを動かします。
Food(餌)を食べると、スネークが大きくなり、自身に当たるとゲームオーバーです。

## confing
```
var config = {
    type: Phaser.WEBGL,
    width: 640,
    height: 480,
    backgroundColor: '#bfcc00',
    parent: 'phaser-example',
    scene: {
        preload: preload,
        create: create,
        update: update
    }
};
```