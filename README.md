# MedSpeak Web版(PWA)

医師のための英語スピーキング特訓アプリ。このフォルダをそのまま HTTPS のサーバーに置くと、
スマホ・PCで「アプリとしてインストール」でき、オフラインでも動きます。

## GitHub Pages で公開する(無料・約5分)

1. GitHub にログインし、右上の「+」→「New repository」。名前(例: `medspeak`)を入れて **Public** で作成
2. 「uploading an existing file」を押し、このフォルダの中身(`index.html`・`manifest.webmanifest`・`sw.js`・アイコンのPNG 4つ)をまとめてドラッグ&ドロップ →「Commit changes」
3. リポジトリの「Settings」→「Pages」→ Branch を `main` / `/(root)` にして「Save」
4. 1〜2分後、`https://<ユーザー名>.github.io/medspeak/` で開けます

旧版(MedSpeak 1.x)を同じURLで公開していた場合は、`index.html` を置き換えるだけで進捗がそのまま引き継がれます。

## アプリとして使う

- **iPhone / iPad**: Safari で開く → 共有ボタン →「ホーム画面に追加」
- **Android**: Chrome で開く → メニュー →「アプリをインストール」
- **Mac / Windows**: Chrome・Edge のアドレスバー右の「インストール」ボタン

## メモ

- マイクでの採点は Chrome・Edge・Safari で使えます(初回にマイクの許可を求められます)。
- AI会話は「設定 → AI会話」で Claude の API キーを入れると使えます。キーはその端末のブラウザ内にだけ保存されます。
- 学習データは各端末のブラウザ内に保存されます。「設定 → データ → 書き出し」で定期的にバックアップしてください。
