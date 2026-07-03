# 🌐 Token Explorer Hub - トークン解析リンク生成ツール

Token Explorer Hub は、暗号資産のコントラクトアドレス（CA）を入力するだけで、主要なブロックエクスプローラーやチャート解析、セキュリティ診断サイトへのダイレクトリンクを瞬時に生成・一括起動できる、Webフロントエンドハブです。

特に **Base Mainnet** などのトークン解析プロセスを大幅に効率化するために設計されています。

---

## ✨ 主な機能

- **🚀 ワンクリック解析リンク生成**
  - コントラクトアドレスを入力するだけで、Basescan（Holders / Contract）、Dexscreener、DEXTools、Uniswap、CubiTech などの主要サイトへの個別リンクを生成します。
- **⚡ 主要リンクの一括起動 (Bulk Open)**
  - 「主要リンクを一括起動」ボタンを押すことで、調査に必要な複数のタブを同時に開き、分析にかかる時間を極限まで削減します。
- **💾 最近検索したトークンの履歴保存**
  - ローカルストレージを活用し、直近に検索したトークンを自動で記録。いつでも過去のトークン情報にワンクリックでアクセスできます。
- **🎨 プレミアム・ダークモードデザイン**
  - 深いブルーとグレーを基調とした洗練されたインターフェース。バックグラウンドには滑らかなグラデーションを配置し、目に優しいモダンなUIを提供します。

---

## 🛠️ 技術スタック

- **Structure**: HTML5
- **Styling**: Tailwind CSS (CDN)
- **Icons**: Lucide Icons
- **Typography**: Google Fonts (Noto Sans JP)

---

## 📂 ディレクトリ構成

```text
token-explorer-hub/
├── index.html        # アプリケーションのメインHTML (UI & JavaScriptロジック)
├── README.md         # この説明ドキュメント
└── .github/
    └── workflows/
        └── deploy.yml # GitHub Pages 自動デプロイ用ワークフロー
```

---

## 🚀 デプロイと利用方法

### ローカルでの利用
1. `index.html` を任意のブラウザでダブルクリックして開くだけで、サーバーなしで動作します。

### GitHub Pages での公開
本リポジトリは GitHub Actions を用いた GitHub Pages の自動デプロイに対応しています。
`main` ブランチにプッシュするだけで、以下のURLにて一般公開されます：
https://dma-cmyk.github.io/token-explorer-hub/

---

## 🛡️ ライセンス

This project is open-sourced under the MIT License.

