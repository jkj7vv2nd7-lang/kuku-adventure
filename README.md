# 九九アドベンチャー（ククと九九の島）

子ども向け九九学習アプリ。単一ファイル `index.html` だけで動作します（外部ファイル・通信不要、進捗は端末内に保存）。

## GitHub Pages で公開する手順

1. GitHub で新しいリポジトリを作成（例：名前 `kuku-adventure`、Public）
2. リポジトリ画面で **Add file → Upload files** を選び、このフォルダの `index.html`（と任意で `README.md`）をアップロードして Commit
3. リポジトリの **Settings → Pages** を開く
4. **Build and deployment** の Source で **Deploy from a branch** を選び、Branch に **main / (root)** を指定して Save
5. 数分待つと、Pages の画面に公開URLが表示されます

公開URLの形式： `https://<ユーザー名>.github.io/kuku-adventure/`

スマホでそのURLを開き、ブラウザの「ホーム画面に追加」をするとアプリのように起動できます。

## 使い方メモ

- 初回はプロフィールのタマゴをタップして「クク」を孵化させます
- 音声入力（🎤）はブラウザ依存です。Chrome（Android）などで動作し、非対応環境では自動的に数字タップ入力のみになります
- 読み上げは端末の音声合成（日本語）を使います。声が出ない場合は端末の音量と、アプリ内「せってい」の「ククの声」を確認してください
- 進捗データは各端末のブラウザ内に保存されます。端末を変えると引き継がれません
