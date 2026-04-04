# GitHub Copilot CLI プレゼンテーション テンプレート

[GitHub Copilot CLI](https://docs.github.com/en/copilot/concepts/agents/copilot-cli/about-copilot-cli) をプレゼンツールとして使うためのテンプレートリポジトリです。

## 使い方

### 1. スライド内容を編集する

`.github/copilot-instructions.md` を開き、`## 見出し` 単位でスライドを記述します。各 `##` が 1 枚のスライドになります。

### 2. プレゼンを開始する

このリポジトリのディレクトリで GitHub Copilot CLI を起動し、プレゼンの開始を依頼します。

```
copilot
```

対話セッションが始まったら、以下のように話しかけます。

```
プレゼンを開始して
```

スキルが自動で `.github/copilot-instructions.md` を読み取り、最初のスライドから表示を始めます。

### 3. スライドを操作する

スライド表示後に選択肢が表示されます。

- **次へ** — 次のスライドに進む
- **前へ** — 前のスライドに戻る
- **スライド一覧** — 全スライドの一覧から選んでジャンプ
- **終了** — プレゼンを終了する

## スライドの書き方

```markdown
## スライドタイトル

本文をここに書きます。
- 箇条書き
- コードブロック
- 段落など Markdown の記法が使えます
```

## 必要なもの

- [GitHub Copilot CLI](https://docs.github.com/en/copilot/how-tos/set-up/install-copilot-cli) — `copilot` コマンドとしてインストール
- GitHub Copilot のサブスクリプション（Free / Pro / Pro+ / Enterprise いずれか）
