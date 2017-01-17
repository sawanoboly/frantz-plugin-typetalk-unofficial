## Franzのtypetalk用非公式プラグイン

です。web版を表示するだけ。

- [meetfranz/plugins: Franz Plugin Repository](https://github.com/meetfranz/plugins)
- [Franz Pluginを作ってみよう - Qiita](http://qiita.com/kan/items/571b2f56c54e1e3b6516) 

を参考に作りました。

ロゴは下記サイトで配布しているEPSをSVGに変換してます。

[ロゴダウンロード - ヌーラボ [Nulab Inc.]](https://nulab-inc.com/ja/logos/)

再配布になっちゃうので、問題があればロゴだけ消します。

## インストール

ファイルをプラグインのディレクトリに転換します。

- Mac: `~Library/Application Support/Franz/Plugins/`
- Windows: `%appdata%/Franz/Plugins`
- Linux: `~/.config/Franz/Plugins`

このように配置でOK。

```
 $ tree Plugins/
Plugins/
└── typetalk-unofficial
    ├── README.md
    ├── icon.png
    ├── icon.svg
    ├── index.js
    ├── package.json
    └── webview.js
```

