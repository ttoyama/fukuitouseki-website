# 福井県透析施設ネットワーク 公式サイト

<https://fukuitouseki.com>

素の HTML 一枚で構成しています。ビルドは不要です。`index.html` を編集して push すると GitHub Pages に反映されます。

## 構成

| ファイル | 役割 |
|---|---|
| `index.html` | トップページ。CSS は内部に書いています |
| `CNAME` | GitHub Pages のカスタムドメイン設定 |
| `.nojekyll` | Jekyll のビルドを止めます |

## 公開の仕組み

GitHub Pages（`main` ブランチのルート）で配信しています。DNS はお名前.com で管理し、apex ドメインを GitHub Pages の IP に向けています。

## 注意

災害透析マニュアル本体は別リポジトリ（private）で管理しています。完成するまでこのサイトには置きません。
