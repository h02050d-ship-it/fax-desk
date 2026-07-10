# 📠 FAXデスク（fax-desk）

林材木店のeFax送受信ツール。メール感覚でFAXを送信し、受信FAXのステータス（未対応／要返信／返信済／対応済）を管理する。

- 画面: GitHub Pages（このリポジトリの index.html）
- データ: Google Apps Script Web App（GAS側ソースは非公開・ローカル `gas/` で管理）
- 送信: `81+FAX番号@efaxsend.com` へのメール送信（件名・本文＝送付状、添付＝FAX原稿）
- 受信: eFax受信メール（message@inbound.efax.com）を台帳化
- 送信結果: eFax完了/失敗通知（send@mail.efax.com）を自動突合
