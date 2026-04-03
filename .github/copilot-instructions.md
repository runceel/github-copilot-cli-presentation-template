# Copilot Instructions

このファイルは、このリポジトリのプレゼンテーション内容を定義する source of truth です。
プレゼンとしての振る舞いは skill 側で扱い、このファイルはスライドに載せる内容に集中します。

## 表紙

- イベント: Project Build Quarterly 懇親会（第1回）
- 開催日: 2026/04/03
- セッションタイトル: GitHub Copilot CLI でプレゼンしてみた
- 登壇者: Kazuki Ota

## 自己紹介

- 名前: 大田 一希 (Kazuki Ota)
- 所属: 日本マイクロソフト Cloud Solution Architect & Evangelist
- 好きな技術: C#, Azure Functions, GitHub Copilot, ゲーム
- X (Twitter): @okazuki
- Zenn: https://zenn.dev/okazuki

## CLI はなんかかっこいい

自分はGUIが好きだけどエンジニアだとCLI（ターミナル）で色々やってる人は何かかっこいいというイメージがある。

## GitHub Copilot CLI が楽しい

一番高機能 GitHub Copilot は GitHub Copilot CLI だと思う。
意外と TUI でもリッチな体験ができる。
選択肢が出るとか。
マウスを持たなくても矢印キーと Enter だけで完結するのがいい。

## プレゼンも CLI でできるんじゃないか？

GitHub Copilot CLI でプレゼン資料を表示するスキルを作ってみた。
この資料は `.github/copilot-instructions.md` にコンテンツを書いていて、スキルがそれを読み取ってスライド表示する。

## どうやって作った？
GitHub Copilot CLI にお願いをしてスキルを作ってもらった。
「プレゼンっぽく動くスキルを作って」
「ask_user で次へ・前へ・スライド一覧を選べるようにして」
「スライドの内容はこのファイルから読み取るようにして」
みたいな感じで。

## まとめ
エンジニアが主な対象のイベントのLTセッションでは、CLIでプレゼンするのも面白いんじゃないかと思う。
GitHub Copilot CLI 自体のデモにもなる。