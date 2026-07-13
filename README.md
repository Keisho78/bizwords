# ビジネス単語帖

その日出会ったビジネス用語を記帳して復習する、単一HTMLの単語帳アプリ（PWA）。
データは端末の localStorage に保存されます。

## 公開URL

GitHub Pages で公開しています → **https://Keisho78.github.io/bizwords/**

（`Keisho78` と `bizwords` は実際のアカウント名・リポジトリ名に置き換わります）

## スマホでアプリとして使う

1. 上記URLを Safari（iPhone）/ Chrome（Android）で開く
2. 共有メニュー →「ホーム画面に追加」
3. アイコンから全画面で起動できます（オフラインでも可）

## 構成

- `index.html` … アプリ本体（React + Babel をCDN読込）
- `manifest.webmanifest` … PWA設定
- `sw.js` … Service Worker（オフラインキャッシュ）
- `icon-*.png` / `apple-touch-icon.png` … アイコン
