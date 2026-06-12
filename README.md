# Claude Code Prompt Builder

> AIに渡す完全な指示セットを、会話するだけで自動生成するClaude Codeスキル

[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blue)](https://code.claude.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![日本語](https://img.shields.io/badge/言語-日本語-red)](README.md)

---

## これは何？

**Claude Code Prompt Builder** は、「何を作りたいか」を伝えるだけで、  
どんなAIツールにもそのまま渡せる **完全な指示セット（プロンプト）** を生成するスキルです。

その分野の専門家・コンサルタントとしてヒアリングしながら、  
Anthropic公式手法と世界的なプロンプト技術を組み合わせて最適な指示セットを作ります。

### こんな人に向いています
- AIに何を・どう伝えればいいかわからない初心者
- 毎回ゼロからプロンプトを考えるのが面倒な人
- SNS自動化・サイト構築・業務効率化などを始めたい人
- Claude Code / Claude Cowork を使い込みたい人

---

## 対応している用途

| カテゴリ | 具体例 |
|---------|--------|
| SNS・コンテンツ | Threads/X/Instagram投稿自動化・ブログ記事作成 |
| ウェブサイト | LP・企業サイト・ECサイト・ポートフォリオ |
| アプリ・システム開発 | Webアプリ・スマホアプリ・CLIツール |
| 自動化システム | API連携・ワークフロー自動化・定期実行 |
| 業務効率化 | Excel自動化・メール整理・レポート生成 |
| コード | レビュー・デバッグ・リファクタリング |
| 文書・メール | ビジネスメール・提案書・報告書 |
| その他 | 上記以外もWebで調べながら対応します |

---

## インストール方法

### Mac / Linux
```bash
# Claude Codeのスキルフォルダにコピーするだけ
cp -r prompt-builder ~/.claude/skills/
```

### Windows
```
prompt-builder フォルダを以下の場所にコピー：
C:\Users\[ユーザー名]\.claude\skills\prompt-builder\
```

### 確認方法
Claude Code を起動して `/prompt-builder` と入力するとスキルが起動します。

---

## 使い方

### 基本的な使い方
```
/prompt-builder
```
を起動してから、やりたいことを話しかけるだけです。

```
例：「Threadsを自動化したい」
例：「会社のウェブサイトを作りたい」
例：「毎朝のメール整理を自動化したい」
例：「ブログ記事を書くプロンプトが欲しい」
```

### 動作の流れ
```
1. やりたいことを伝える
        ↓
2. 専門家として1問ずつヒアリング
   （選択肢＋おすすめ＋理由をセットで提示）
        ↓
3. 既存ツール・環境を確認
        ↓
4. 完全な指示セットを生成
   ・通常プロンプト（ChatGPT等にコピペして使う）
   ・Claude Code実行型（貼るだけで完成まで動く）
        ↓
5. コスト試算を自動出力（自動化・開発系の場合）
        ↓
6. セキュリティ注意事項（APIキーを使う場合）
        ↓
7. テスト→フィードバック→改善を完成まで繰り返す
```

---

## 特徴

### 🤝 最後まで離れない伴走型
プロンプトを渡して終わりではありません。  
実装・テスト・エラー解決・完成確認まで一緒に進みます。

### 🔍 動的に情報を取りに行く
料金・API仕様・最新ツールなど古くなりやすい情報は  
WebSearch / WebFetch で都度確認してから回答します。

### 💡 正直なコンサルタント
「なんでもYES」ではなく、方向性がズレていれば正直に指摘し  
より良い代替案を提案します。

### 🔒 セキュリティを忘れない
APIキーや認証情報を扱う場合、安全な管理方法を必ず案内します。

### 💰 コストを見える化
自動化システム構築時は月額コスト試算を自動で出力します。

---

## 組み込まれている知識

### Anthropic 公式（`knowledge/anthropic.md`）
- プロンプトエンジニアリング チュートリアル全9章
- Anthropicの「80/20ルール」
- Claude Code / Cowork 特有のベストプラクティス

### 世界的な手法（`knowledge/global.md`）
- Chain of Thought (CoT)
- Tree of Thought (ToT)
- ReAct（推論と行動の統合）
- Self-Consistency
- Few-shot / Many-shot
- CO-STAR・RISENフレームワーク
- メタプロンプティング
- その他11手法

---

## ファイル構成

```
prompt-builder/
├── SKILL.md          # スキル本体（動作指示・ヒアリングフロー）
├── README.md         # このファイル
└── knowledge/
    ├── anthropic.md  # Anthropic公式プロンプト知識ベース
    └── global.md     # 世界的プロンプト手法集
```

---

## 動作環境

- Claude Code（デスクトップ版・ターミナル版）
- Claude Cowork
- 生成したプロンプトは ChatGPT・Codex 等でも使用可能

---

## フィードバック・改善提案

使ってみて「ここが違う」「こんな機能が欲しい」があれば  
Issue や Pull Request をお気軽にどうぞ。

みなさんのフィードバックでどんどん良くなります。

---

## ライセンス

MIT License — 自由に使用・改変・再配布できます。

---

*Powered by [Claude Code](https://code.claude.com) / Made with ❤️ for Japanese AI users*
