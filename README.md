# GithubActions_playgrounds

GitHub Actionsの学習と実験のためのリポジトリです。

## 📚 公式ドキュメント

GitHub Actionsの詳細な情報は公式ドキュメントを参照してください：
- [GitHub Actions 公式ドキュメント](https://docs.github.com/)

## 🔍 GitHub Actionsの探し方

既存のアクションを探すには、GitHub Marketplaceを利用してください：
- [GitHub Marketplace](https://github.com/marketplace)

## 🖼️ Runnerのイメージ一覧

利用可能なランナーイメージの詳細は以下を参照してください：
- [GitHub Actions Runner Images](https://github.com/actions/runner-images)

## 📋 GitHubイベント一覧

GitHub Actionsで利用可能なイベント（トリガー）の一覧：

### Column 1
- `branch_protection_rule`
- `check_run`
- `check_suite`
- `create`
- `delete`
- `deployment`
- `deployment_status`
- `discussion`
- `discussion_comment`
- `fork`
- `gollum`
- `issue_comment`

### Column 2
- `issues`
- `label`
- `merge_group`
- `milestone`
- `page_build`
- `project`
- `project_card`
- `project_column`
- `public`
- `pull_request`
- `pull_request_comment`
- `pull_request_review`

### Column 3
- `pull_request_review_comment`
- `pull_request_target`
- `push`
- `registry_package`
- `release`
- `repository_dispatch`
- `schedule`
- `status`
- `watch`
- `workflow_call`
- `workflow_dispatch`
- `workflow_run`

## 🚀 学習のポイント

GitHub Actionsを学ぶ際の重要なポイント：

1. **ワークフローファイルの配置**: `.github/workflows/` ディレクトリにYAMLファイルを配置
2. **actions/checkout**: リポジトリのコードをランナーにクローンする基本的なアクション
3. **イベント駆動**: プッシュ、プルリクエストなどのイベントでワークフローを実行
4. **ジョブとステップ**: ワークフローは複数のジョブで構成され、各ジョブは複数のステップで構成

## 📁 このリポジトリの構成

```
.github/
└── workflows/
    └── hello.yml  # 基本的なHello Worldワークフロー
```
