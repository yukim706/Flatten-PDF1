# Flatten-PDF1

Google Drive 上の PDF を再帰的に取得し、  
**フラット化（画像化）＋圧縮**して上書き保存する Python スクリプトです。

処理結果は Google Spreadsheet にログとして記録されます。

---

## ✅ 主な機能

- Google Drive フォルダを **再帰的に探索**
- PDF を **フラット化（リンク保持）**
- 容量を圧縮して **元ファイルを更新**
- 処理ログを **Google Spreadsheet に記録**

---

## ✅ 必要なもの

- Python 3.9 以上
- Google サービスアカウント
- Google Drive API / Sheets API 有効化

---

## ✅ 環境変数の設定（必須）

以下の環境変数を設定してください。

| 変数名 | 内容 |
|------|------|
| `SPREADSHEET_ID` | ログ記録用 Google Spreadsheet の ID |
| `GOOGLE_SERVICE_ACCOUNT` | サービスアカウント JSON（文字列） |

※ **値そのものは公開しないでください**

---

## ✅ 実行方法

```bash
python main.py
``
