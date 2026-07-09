# 日本骨密度プロジェクト — ランディングページ

「100歳まで、自分の足で歩く日本へ。」をミッションに、まず自分の骨密度を知り、
同年代平均を目指す国民運動としてのプロジェクトLP。カルベール（ヘルスィング株式会社）が中核商品。

## 構成
- `index.html` … 単一ファイル完結のLP（ヒーロー画像はデータURIで埋め込み済み、Webフォントのみ CDN 読み込み）

## ローカルで見る
`index.html` をブラウザで開くだけ。

## 公開（GitHub Pages）
1. このリポジトリを push
2. Settings → Pages → Source: **Deploy from a branch** → `main` / `root` → Save
3. 数分後 `https://<owner>.github.io/<repo>/` で表示

## 公開前チェック（本番リリース時）
- [ ] `index.html` 冒頭の `<meta name="robots" content="noindex, nofollow">` を削除（開発中は検索避けのため入れてある）
- [ ] 参加者6名の写真・動画・掲載同意、代表者名・写真、商品写真を差し替え
- [ ] 統計値の出典を確定、申込みフォーム/決済リンクを接続
- [ ] 薬機法・景表法の表現チェック（体験談・「同年代平均以上」コピー等）を専門家レビュー

## メモ
- ヒーロー画像を差し替える場合は、最適化した画像を `index.html` の `.hero-bg` の `src`（data URI）に置き換える
- カルベール本体サイト: https://healthing.jp
