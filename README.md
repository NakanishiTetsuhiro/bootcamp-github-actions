# bootcamp-github-actions
https://docs.github.com/ja/actions/quickstart

## バッチ試してみた
https://docs.github.com/ja/actions/managing-workflow-runs/adding-a-workflow-status-badge#using-the-workflow-file-name

![example workflow](https://github.com/github/docs/actions/workflows/github-actions-demo.yml/badge.svg)

### ワークフローファイル名を使用する
この Markdown の例では、.github/workflow/github-actions-demo.ymlというファイル パスのワークフローにステータス バッジを追加します 。 リポジトリの OWNER は github Organization で、REPOSITORY 名は docs です。
![example workflow](https://github.com/github/docs/actions/workflows/github-actions-demo.yml/badge.svg)

### branch パラメータを使用する
この Markdown の例では、feature-1という名前のブランチにステータス バッジを追加します。
![example branch parameter](https://github.com/github/docs/actions/workflows/github-actions-demo.yml/badge.svg?branch=feature-1)

### event パラメータを使用する
この Markdown の例では、 pull_request イベントによってトリガーされたワークフロー実行のステータスを示すバッジを追加します。
![example event parameter](https://github.com/github/docs/actions/workflows/github-actions-demo.yml/badge.svg?event=pull_request)