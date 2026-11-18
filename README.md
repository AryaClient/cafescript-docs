# CafeScript Language Reference

CafeScript の言語仕様をまとめた静的サイトです。日本語と英語の両方を収録しています。

公開先: <https://aryaclient.github.io/cafescript-docs/>

## 内容

- 概要・字句・プログラム構造
- 名前と名前解決
- 型、構造体・列挙型・ジェネリクス
- 関数・`extern`・`hook`
- 変数・文・式・型変換
- 到達可能性・未定義動作・ABI
- 診断・文法（EBNF）

## 構成

| パス | 内容 |
| --- | --- |
| `index.html` | サイト全体。CSS・JS・全ページを 1 ファイルに含む |
| `.nojekyll` | GitHub Pages の Jekyll 処理を無効にする |

ページ切り替えは URL のハッシュ（`#ja/overview`、`#en/types` など）で行うため、
`index.html` 以外のファイルは不要です。

## ローカルで見る

```sh
python3 -m http.server 8000
# http://localhost:8000/ を開く
```

## 公開

`main` ブランチのルートを GitHub Pages の配信元にしています。
`main` に push すると数十秒で反映されます。

## 注意

コード例のアドレス（`at 0x...`）とオフセットは説明用の値です。
実際の値は対象バイナリの解析結果に依存します。
