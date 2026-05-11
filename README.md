# 価格差分チェッカー

価格表CSVと商品マスターCSVを、SKUコードで突合して価格差分を確認するブラウザツール。

公開URL: https://g-product.github.io/tools/price-diff-checker.html

## 使い方

公開URLにアクセスして、2つのCSVをドラッグ&ドロップするだけ。
価格相違・片側のみのSKUが上に表示されます。

## 仕様

- **対応文字コード**：UTF-8 / UTF-8 BOM / Shift_JIS（自動判定）
- **列の認識**：
  - SKUコード列：「SKUコード」「SKU」を含む列
  - 価格列：「販売価格」「売価」「価格」を含む列
  - 商品名列：「SKU表示名」「SKU名」「商品名」を含む列

## セキュリティ

- ファイルは**ブラウザ内でのみ処理**され、サーバーやネットワークには送信されません
- 外部依存なし（CDNも使っていません）
- ページを閉じればすべて消えます

# tools

業務データの突合・整形ツール集。

## ツール一覧

- [価格差分チェッカー](https://g-product.github.io/tools/price-diff-checker.html) — 価格表CSVと商品マスターCSVの価格差分を確認
- [tabファイルジェネレータ](https://g-product.github.io/tools/tab-generator.html) — 商品マスターCSVから新潟/山形別のtabファイルを生成
