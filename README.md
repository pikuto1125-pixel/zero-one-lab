# Zero-One Venture Lab — 現場特化マイクロSaaS ＆ 実機ショーケース

**公開デモポータル（Cloudflare Edge）**: https://zero-one-lab.ai-hack-lab.workers.dev/

現場・バックオフィス実務の「手戻り・見落とし・二重対応」を社内完結（ローカル処理中心）で解消する 7 つの実機マイクロSaaS・ショーケース群です。

## 主力プロダクト：`SiteProof Studio` V2（施工写真→18秒縦型リール＋A4報告書一括生成）

外壁塗装・外構・造園・内装・中古車仕上げなど、現場写真 4 枚（①施工前・②下地・③施工中・④完了）から以下をローカル処理で一括生成します。

- **1080×1920（9:16）ショート動画（18.00秒 / H.264 + AAC 音声・BGM付）**: Sharp による人物・車番保護対応の画質/構図調整、Ken Burns ズーム＆パン、Before/After 2分割比較、`xfade=wiperight` ワイプ演出、SNS 右側 UI セーフゾーン保護済み日本語テロップを `ffmpeg` で生成
- **1200×640 Before/After 比較 PNG**: 見積・LINE 報告・SNS 投稿にそのまま使える比較画像
- **A4 印刷対応 施工完了報告書 HTML**: 工事区分・工程別 4 枚写真・検査ログ付き（1ページ印刷設計）

### 実機サンプル ＆ 技術記事

- **ポータル全体**: https://zero-one-lab.ai-hack-lab.workers.dev/
- **SiteProof Studio 導入見本（業種別 1080×1920 音声付リール 3 本再生可）**: https://zero-one-lab.ai-hack-lab.workers.dev/samples/sample_v006_siteproof.html
- **SiteProof Studio プロダクトプレビュー**: https://zero-one-lab.ai-hack-lab.workers.dev/ventures/v006_siteproof_studio/dist/public_landing_preview.html
- **技術解説記事（Zenn）**: https://zenn.dev/pikuto/articles/siteproof-sharp-ffmpeg-local-report-video

## 収録プロダクト一覧（全7種）

| # | プロダクト名 | 用途 | 公開プレビュー |
|---|---|---|---|
| 1 | **ThumbStop Arena** | EC画像・動画サムネのスマホ168px実寸縮小＆UI重なり検品 | `/samples/sample_v001_thumbstop.html` |
| 2 | **ReplyGuard Solo** | 受託の仕様追加要望に対する角の立たない見積分岐・返信下書き | `/samples/sample_v002_replyguard.html` |
| 3 | **SlideGate PreFlight** | 営業・登壇スライドの明室プロジェクター白飛び・ボケ再現検品 | `/samples/sample_v003_slidegate.html` |
| 4 | **InvoiceGuard PreFlight** | 買掛請求書の単価桁ズレ・法人番号MOD9検算・二重計上防止 | `/samples/sample_v004_invoiceguard.html` |
| 5 | **SnapLedger PreFlight** | 領収書のインボイス適格要件チェック＆会計仕訳CSV出力 | `/samples/sample_v004_snapledger.html` |
| 6 | **SyncGuard PreFlight** | スプシ×LINE/メール通知のSHA-256二重送信遮断＆未達再送分離 | `/samples/sample_v005_syncguard.html` |
| 7 | **SiteProof Studio** | 現場写真4枚→18秒音声付縦型リール・Before/After・A4完了報告 | `/samples/sample_v006_siteproof.html` |
