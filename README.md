# 第2回 隠しミッション ARフィルター

このセットには、GitHub Pagesで使う `index.html` とクリスマス仕様の透過ARフレームが含まれています。カメラ撮影と、端末に保存した写真の選択の両方に対応します。

## GitHub Pagesへの反映

1. `index.html` と `assets/stellar-ar-frame.png` を、リポジトリのGitHub Pages公開元にアップロードします。
2. Pagesの公開元がブランチのルートならリポジトリ直下に `index.html` を置きます。公開元が `/docs` なら、両方のファイルを `docs` 内に置いてください。
3. `Settings → Pages` で公開元のブランチとフォルダを確認し、変更をコミットします。
4. `Actions` でPagesのデプロイが成功したことを確認してから、公開URLを再読み込みします。

フレームは `index.html` 内に埋め込まず、`assets/stellar-ar-frame.png` から読み込みます。フレームを更新するときは、この画像ファイルを同じ場所・同じ名前で差し替えてください。
