1) ارفع محتويات هذا المجلد مباشرة في أول GitHub repo (api و public و vercel.json في الجذر، بدون مجلد داخلي).
2) Vercel > Settings > Environment Variables: DISCORD_CLIENT_ID, DISCORD_CLIENT_SECRET, SESSION_SECRET (أو املأهم في discord-config.js).
3) Discord Developer Portal > OAuth2 > Redirects: https://اسم-موقعك.vercel.app/api/callback
4) Vercel > Storage > Upstash Redis واربطه، ثم Redeploy.
5) للتأكد: افتح /api/health وكل القيم لازم تكون true.
