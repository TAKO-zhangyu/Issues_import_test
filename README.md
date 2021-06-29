# Issues_import_test

github-csv-toolsの動作確認用リポジトリ
インポートのみを確認した。

- github-csv-tools
https://github.com/gavinr/github-csv-tools
## 手順
1. ```npm install -g github-csv-tools```を実行し、github-csv-toolsをインストール
2. CSVファイルを作成する（場所はPC内であればどこでもよい。実行時に指定する。）
3. GitHubのリポジトリのトークンを作成する -> https://github.com/settings/tokens
4. githubCsvTools CSVファイル名を実行する

## 追記
**トークンに関して（公式GitHubから引用、翻訳）**
1. このリンクに遷移 -> https://github.com/settings/tokens
2. "Generate New Token"をクリック
3. "repo" をクリック
4. コピーする。実行時にトークンを求められたときに貼り付けて実行する。

**CSVファイルの作成に関して**
- Markdownの記述について
タイトルと説明文のみの場合、以下のような記述でMarkdown記法が使用できる
---
タイトル,"## タイトルテスト

- リスト

```
コード
```
"
---

