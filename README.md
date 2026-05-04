# ENISHI Price List

ENISHI（株式会社ENISHI）の多通貨対応・卸売価格リスト Web App。

## 公開URL

https://atsuki1860.github.io/enishi-pricelist/

## 構成

- `index.html` — フロントエンド（多通貨カート・住所入力・Send Order Inquiry）
- `config.js` — Google Apps Script Web App URL の設定
- 価格・為替データ：Google Apps Script API（JSON）から動的取得

## 技術スタック

- Frontend: HTML / CSS / Vanilla JavaScript
- Backend: Google Apps Script（Web App）+ Google Sheets
- Hosting: GitHub Pages
- Email: MailApp（GAS 経由）

## 対応通貨

USD / EUR / GBP / CAD / AUD / SGD

## 対応支払方法

- Wise（0% commission・推奨）
- PayPal（+5% commission）

## 法人情報

株式会社ENISHI（法人番号 1290001103524）  
代表：加藤 充貴
