# とわのメモ帳（towa-memo）

ログインの練習用アプリ（Year 1・10本目）。GitHubのアカウントでログインし、ログインした人の名前と、本人だけのメモの箱を表示する。

- 公開URL: https://towa-memo.pages.dev/
- 次の段階: データベースで、メモを本人だけが読み書きできるようにする（2026年10月末）

- ログインの受付係: Supabase（Auth・GitHubログイン）
- 置き場所: Cloudflare Pages（`public/` だけを公開）
- ⚠️ `public/index.html` に書いてよいのは Supabase の「公開してよい鍵」（`sb_publishable_`）だけ。秘密の鍵（`sb_secret_`）は書かない

---

# Towa's Memo (towa-memo)

A practice app for sign-in (Year 1, app #10). Live: https://towa-memo.pages.dev/ Sign in with GitHub via Supabase Auth; the page shows who is signed in. Hosted on Cloudflare Pages (only `public/` is deployed).
