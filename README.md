# OCR Webアプリケーション

このアプリは画像から文字を抽出し、LaTeX形式やテキスト形式で表示・コピーができるWebベースのOCRツールです。

## 📦 機能

- 画像をアップロードしてOCR解析
- 日本語・英語・数式の認識に対応
- LaTeX形式またはテキスト形式で結果を取得可能
- 結果をワンクリックでコピー
- ダークモード対応

## 🖥️ 使用技術

- Python（Bottleフレームワーク）
- JavaScript（Cropper.jsなど）
- HTML + CSS
- Tesseract OCR（バックエンド側）

## 🚀 使い方

1. このリポジトリをクローン：
   ```bash
   git clone https://github.com/AYUFA/OCR.git
   cd OCR

2. 必要なライブラリをインストール：
```bash
   pip install bottle pillow pytesseract

3. サーバーを起動：
```bash
   python app.py
   
4. ブラウザで開く：
```arduino
   http://localhost:8080
   
5. 画像をアップロードして、結果を確認＆コピー！

## 📂 ディレクトリ構成

```bash
OCR/
├── app.py              # アプリのエントリポイント
├── bottle.py           # Bottleマイクロフレームワーク
├── main.js             # 画像処理とアップロード制御
├── result.js           # テキスト用JS
├── latex_result.js     # LaTeX用JS
├── style.css           # スタイル
├── views/              # テンプレート群
│   ├── index.tpl
│   ├── result.tpl
│   ├── latex_result.tpl
│   └── latex_text_result.tpl
## 📄 ライセンス

MIT License


---

## 📝 手順

この内容をコピーして、OCR フォルダの中に README.md という名前で保存してください。  
保存後、GitHubに反映するには以下を実行：

```bash
git add README.md
git commit -m "Add README.md"
git push
