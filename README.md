# 確定申告アプリ

個人事業主向け・青色申告（複式簿記65万円控除）対応の会計アプリ。単一HTML。

- **アプリ本体**：`index.html`（このファイルを直接編集する。ビルドなし）
- **公開URL**：https://pianoshop1214-commits.github.io/kaikei/
- **データの保存先**：非公開リポジトリ `kaikei-data`（帳簿JSON＋レシート画像）
- **APIキー・GitHubトークン**：各端末のブラウザ（LocalStorage）にのみ保存。このリポジトリには含まない

## デプロイ

`index.html` を編集して push すると GitHub Pages に自動反映される。

```
git -C tools/kaikei-app commit -am "更新内容" && git -C tools/kaikei-app push
```
