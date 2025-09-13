# Git Practice Repository

This repository is a sandbox for practicing Git commands. It's a learning playground for exploring common Git workflows such as branching, merging, rebasing, and remote operations.

## 概要
Git Practice Repository は、Git の基本操作を安全に練習・理解するためのリポジトリです。ブランチ操作、マージ／リベース、リモートの操作、コミット履歴の読み解きなどを実習します。

## 技術スタック
- 言語/フレームワーク: なし（学習用の Git 操作リポジトリ）
- バージョン管理: Git
- インフラ/CI: なし（現時点のリポジトリ構成には CI/CD ワークフローは含まれていません）

---

## 主な機能一覧
- ブランチ作成・切替・削除の演習
- マージとリベースの演習とコンフリクト解決の体験
- ローカルリポジトリとリモートリポジトリ間のフェッチ／プッシュ／プルの練習
- コミット履歴の作成規約と読み取りの演習

---

## 設計・実装の工夫
- 学習用サンドボックスとして、実際のアプリケーションコードを含めず、Git 操作の演習に焦点を当てる構成
- README を中心に演習手順とベストプラクティスをまとまた読みやすいドキュメントにする設計
- ブランチ名・PRフローの例を示すことで、実務的なワークフローの理解を促進

---

## セットアップ & 動作確認方法

セットアップ
- リポジトリをクローン
  - git clone https://github.com/nemdull/git-practice.git
  - cd git-practice

動作確認の基本コマンド例
- 基本情報の確認
  - git status
  - git log --oneline --decorate --graph --all
- ブランチ操作の練習
  - git branch
  - git checkout -b your-feature-branch
  - git merge your-feature-branch
- リモート操作の練習
  - git fetch origin
  - git push origin your-feature-branch
  - git pull origin main

---

## 改善ポイント / TODO
- テスト
  - [ ] 現状、リポジトリにはテストファイルが含まれていません。追加検討を推奨
- エラーハンドリング
  - [ ] 具体的なエラーハンドリングの実装は現状なし（演習用の性質上、実動アプリとは異なる）
- 設計
  - [ ] README の完全版化を優先して、見出し構成とセクションの統一感を高める
- ドキュメント
  - [ ] より詳しい演習手順の図解・サンプルセッションを追加
- CI/CD
  - [ ] GitHub Actions 等のワークフローの追加検討（現状なし）

---

## 強調したいポイント
- 本リポジトリは「技術力」「設計力」「改善意識」を示す実例として活用可能
- 実務の Git ワークフローを体感できる教材として設計

---

## 参考情報
- origin: https://github.com/nemdull/git-practice.git
- 最終コミット (参考): e60cd9663b84e795c53518fe5222282b69bf6c49
