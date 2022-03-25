# Contributing to Our Project

私たちは、このプロジェクトにできるだけ簡単に、そして透明性をもって貢献できるようにしたいと考えています。
以下は貢献する方法のいくつかの例です。

* バグを報告する
* コードの現状を議論する
* 修正コードを提出する
* 新しい機能を提案する
* メンテナーになる

## We Develop with Github

私たちは、バグレポートや機能追加の要求、プルリクエストの受付にGitHubを使用しています。

### Submit Code Changes Via Pull Request

コードの変更を提案するには、GitHub PRsが最適です。
私たちはあなたのプルリクエストを積極的に歓迎します。

1. リポジトリをフォークし、`main`からブランチを作成します。
2. テストすべきコードを追加した場合は、テストを追加してください。
3. APIを変更した場合は、ドキュメントを更新してください。
4. テストがパスすることを確認してください。
5. コードが整形されていることを確認してください。
6. プルリクエストを発行してください。

### Report Bugs or Request Features Using Issue

私たちはGitHub Issuesを使用し、公開されたバグや機能追加の要求を追跡しています。
また私たちのOrganizationでは、Issuesにテンプレートを用意しています。
今のところは以下の三つです。

* 🐛 Bug
* ✨ Enhancement
* 🔍 Investigation

これらを使用して、**皆から愛される**Issuesを作成してください。
もし、あなたの表現力がこれらのテンプレートを追い越してしまった場合は、テンプレートを追加してほしい旨のIssuesを提出してください。

## Use a Consistent Styles

commit履歴やコーディングスタイルを一貫させることは、あなたにとっても私たちにとっても重要なことです。
私たちが守るべき開発規約には、以下のようなものがあります。

### Branches

* 使用するブランチは[GitHub Flow](https://docs.github.com/ja/get-started/quickstart/github-flow)に従い、以下とする。
  * `main`: 常にデプロイ可能なブランチ
  * `develop`: 統合ブランチ
  * `feature-*`: 新機能開発ブランチ
  * `fix-*`: 問題修正ブランチ
* `main`ブランチおよび`develop`ブランチのcommitには、[Git Commit Message Editor](https://marketplace.visualstudio.com/items?itemName=phoihos.git-commit-message-editor)を使用する。
* `main`ブランチおよび`develop`ブランチを無許可pushから保護する。
  ただし`develop`ブランチへのmergeは、CIが通過していればプルリクエストが承認されていなくても実行することができる。
* プルリクエスト承認後のmergeには以下の方法を使用する。
  * `develop`→`main`: *Create a merge commit*
  * `feature-*/fix-*`→`develop`: *Squash and merge*

### Coding

* `main`ブランチおよび`develop`ブランチにmergeするコードは、リンタやフォーマッタによって最低限のフォーマットがなされている必要がある。

## References

この文書は、[こちら](https://gist.github.com/briandk/3d2e8b3ec8daf5a27a62)の貢献ガイドラインを参考に作成されました。