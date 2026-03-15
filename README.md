# 🎨 AnimePrompt Studio

アニメ系AIイラスト生成のためのプロンプトビルダーです。  
Stable Diffusion / NovelAI などの画像生成AIに使えるプロンプトを、直感的なUIで簡単に作成できます。

![HTML](https://img.shields.io/badge/HTML-単一ファイル-e040fb?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-7c4dff?style=flat-square)

---

## ✨ 機能

- **テンプレート選択** — セーラー服・巫女・メイドなど多彩なキャラクタースタイル
- **衣装カスタマイズ** — 衣装タイプ・カラー・トップス・ボトムス・アクセサリーなどを細かく設定
- **パラメータ調整** — 画質・アートスタイル・カメラアングル・照明・背景などをドロップダウンで選択
- **タグ追加** — 感情・ポーズ・エフェクトなどのタグをワンクリックで追加
- **ネガティブプロンプト自動生成** — テンプレートに最適化されたネガティブプロンプトを自動で出力
- **ランダム生成** — 全パラメータをランダムに組み合わせてプロンプトを一発生成
- **クリップボードコピー** — 生成したプロンプトをワンクリックでコピー

---

## 🚀 使い方

単一のHTMLファイルで動作します。インストール不要です。

```bash
# リポジトリをクローン
git clone https://github.com/siamiko/anime-prompt-studio.git

# ファイルをブラウザで開くだけ
open anime-prompt-generator.html
```

またはファイルをダウンロードして、ブラウザにドラッグ＆ドロップするだけで使えます。

---

## 🎮 対応ツール

生成されたプロンプトは以下のツールで使用できます：

- [Stable Diffusion WebUI (AUTOMATIC1111)](https://github.com/AUTOMATIC1111/stable-diffusion-webui)
- [NovelAI](https://novelai.net/)
- [ComfyUI](https://github.com/comfyanonymous/ComfyUI)
- その他 Danbooru タグ形式に対応したツール全般

---

## 🛠️ 技術スタック

- 純粋な HTML / CSS / JavaScript（フレームワーク不使用）
- 外部依存：[Google Fonts](https://fonts.google.com/)（Rajdhani / Noto Sans JP）のみ
- サーバー不要・データ送信なし・完全ローカル動作

---

## 📄 ライセンス

[MIT License](LICENSE) © 2025 siamiko

---

## 🤝 コントリビュート

バグ報告・機能提案は [Issues](https://github.com/siamiko/anime-prompt-studio/issues) へ。  
プルリクエストも歓迎です！
