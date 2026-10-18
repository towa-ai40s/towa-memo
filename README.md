# とわのメモ帳（towa-memo）

ログインの練習用アプリ（Year 1・認証①）。GitHubのアカウントでログインし、ログインした人の名前を表示する。

- ログインの受付係: Supabase（Auth・GitHubログイン）
- 置き場所: Cloudflare Pages（`public/` だけを公開）
- ⚠️ `public/index.html` に書いてよいのは Supabase の「公開してよい鍵」（`sb_publishable_`）だけ。秘密の鍵（`sb_secret_`）は書かない

---

# Towa's Memo (towa-memo)

A practice app for sign-in (Year 1, auth step 1). Sign in with GitHub via Supabase Auth; the page shows who is signed in. Hosted on Cloudflare Pages (only `public/` is deployed).
