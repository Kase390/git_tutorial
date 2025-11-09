# practiceGit

Git の基本操作を試すためのミニプロジェクトです。`index.html` と `home.html` を使って、ステージングやコミット、ブランチ操作などの練習ができます。

## 使い方

1. このリポジトリをクローン: `git clone https://github.com/Kase390/git_tutorial.git`
2. 任意のファイルを編集して `git status` で差分を確認
3. `git add <file>` でステージングし、`git commit -m "<message>"` でコミット
4. 練習が終わったら `git push origin main` で GitHub に送信

## ESLint

`eslint.config.mts` に設定を置いているので、必要に応じて `npx eslint .` で静的解析できます。VSCode を使う場合は拡張機能 (ESLint) を入れておくと便利です。

## 備考

- `index.html` は Git コマンドのメモを兼ねています。
- `home.html` は `git pull` の練習に使う予定のファイルです。
- 学習内容に応じて README や HTML を自由に更新してください。
