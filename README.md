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

| イベント名 | 説明 | 用途 |
|-----------|------|------|
| `push` | コードがプッシュされた時 | 基本的なCI/CD |
| `pull_request` | プルリクエストが作成/更新された時 | コードレビュー前のテスト |
| `issues` | イシューが作成/更新された時 | イシュー管理の自動化 |
| `release` | リリースが作成された時 | リリース時の自動処理 |
| `schedule` | 定期的な実行 | 定期メンテナンス |
| `workflow_dispatch` | 手動実行 | デバッグや緊急時 |
| `create` | ブランチ/タグが作成された時 | 新機能開発の開始 |
| `delete` | ブランチ/タグが削除された時 | クリーンアップ処理 |
| `fork` | リポジトリがフォークされた時 | フォーク時の処理 |
| `public` | リポジトリが公開された時 | 公開時の処理 |
| `watch` | リポジトリがスターされた時 | 統計収集 |
| `gollum` | Wikiページが更新された時 | Wiki管理 |
| `page_build` | GitHub Pagesがビルドされた時 | ページ管理 |
| `status` | コミットステータスが更新された時 | ステータス管理 |
| `check_run` | チェック実行が完了した時 | テスト結果処理 |
| `check_suite` | チェックスイートが完了した時 | テストスイート管理 |
| `deployment` | デプロイメントが作成された時 | デプロイ管理 |
| `deployment_status` | デプロイメントステータスが更新された時 | デプロイ監視 |
| `milestone` | マイルストーンが更新された時 | プロジェクト管理 |
| `project` | プロジェクトが更新された時 | プロジェクト管理 |
| `project_card` | プロジェクトカードが更新された時 | プロジェクト管理 |
| `project_column` | プロジェクトカラムが更新された時 | プロジェクト管理 |
| `label` | ラベルが更新された時 | ラベル管理 |
| `discussion` | ディスカッションが更新された時 | コミュニティ管理 |
| `discussion_comment` | ディスカッションコメントが更新された時 | コミュニティ管理 |
| `issue_comment` | イシューコメントが更新された時 | コメント管理 |
| `pull_request_comment` | プルリクエストコメントが更新された時 | レビュー管理 |
| `pull_request_review` | プルリクエストレビューが更新された時 | レビュー管理 |
| `pull_request_review_comment` | プルリクエストレビューコメントが更新された時 | レビュー管理 |
| `pull_request_target` | フォークからのプルリクエスト | セキュリティ考慮 |
| `registry_package` | パッケージが公開された時 | パッケージ管理 |
| `repository_dispatch` | 外部からのイベント | 外部システム連携 |
| `workflow_call` | 他のワークフローから呼び出し | ワークフロー再利用 |
| `workflow_run` | ワークフローが完了した時 | ワークフロー連携 |
| `merge_group` | マージグループが更新された時 | マージ管理 |
| `branch_protection_rule` | ブランチ保護ルールが更新された時 | セキュリティ管理 |

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
