# Game Hav

Phaserで作成したゲームを、 GitHabから読み込むことができます。

## スタートガイド

### Phaserのファイル構造
![](assets/sc01)
このように、ファイルを作成してください。ゲームで使用するテクスチャなどのpngファイルはassets直下に配置します。

また、main.js内でロードする時は、次のようにパスを指定します。
```
function preload ()
{
    this.load.image('food', 'assets/food.png');
    this.load.image('body', 'assets/body.png');
}
```
Game-Havでは自動でGitHubのリンクに置き換えられます。
```
function preload ()
{
    this.load.image('food', 'https://raw.githubusercontent.com/IWK623/game00/main/assets/food.png');
    this.load.image('body', 'https://raw.githubusercontent.com/IWK623/game00/main/assets/body.png');
}
```

### リンク作成
https://game-hav.web.app/game/
リンクにアクセスし、GitHubのアカウント名と、リポジトリ名を入れてリンクを作成できます。
作成したリンクはSNSでシェアし、誰でもあなたが作成したゲームで遊ぶことができます。
