# vietnam-trip-site プロジェクト

## 概要
ベトナム旅行（2026年）の旅のしおりサイト。

- メインファイル: `index.html`
- GitHub: https://github.com/kachiq94u9dj/vietnam-trip-2026
- Vercel プロジェクト: `vietnam-trip-2026`

## デプロイ設定

### 自動デプロイ（post-commit フック）
`git commit` を実行するたびに以下が自動で走る：
1. `git push origin HEAD` — GitHubにプッシュ
2. `vercel --prod --yes` — Vercel本番環境にデプロイ

フック場所: `.git/hooks/post-commit`

### 手動デプロイ
```bash
git push origin HEAD
vercel --prod
```
