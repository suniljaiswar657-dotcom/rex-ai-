# InstaFlow OS

Offline-first Instagram content planning dashboard. Built as a static web app for quick GitHub Pages/Vercel deployment.

## Features
- Responsive neon dark UI
- Caption and hashtag template generator (offline-safe, not live AI)
- Local draft and queue storage
- Idea vault, JSON export, PWA service worker
- Queue records are planning only; no Instagram publishing occurs in this demo

## Deploy on Vercel
1. Open the Vercel dashboard and choose **Add New → Project**.
2. Import `suniljaiswar657-dotcom/rex-ai-` from GitHub.
3. Framework preset: **Other**; build command and output directory can remain blank/default for static files.
4. Deploy. Pushes to the connected production branch will trigger redeployment.

## To enable real Instagram automation
Requires an eligible Instagram Professional account, a Meta developer app, OAuth and approved permissions, a secure server-side token store, and a backend queue/scheduler. Do not put access tokens in browser code. Offline mode cannot post, send DMs, or fetch live insights.
