# Meal Palette — GitHub Pages 修正版

公開先: https://knwj5dvvrc-ctrl.github.io/Meal-Palette/

## 更新方法

ZIPを解凍し、**中のファイルをリポジトリのルート**へアップロードしてください（フォルダごと入れない）。GitHub Pages の Settings → Pages で `Deploy from a branch`、`main`、`/(root)` を使用している場合の手順です。

変更点: manifest の start_url / scope を `/Meal-Palette/` に修正。Service Worker の登録とキャッシュパスを相対パスに変更。古いキャッシュを消す処理を追加。

公開後はSafariでURLを開き、既存のホーム画面アイコンを削除してから再追加してください。

データはブラウザ内に保存されるため、SafariのWebサイトデータ削除はバックアップを取ってから行ってください。
