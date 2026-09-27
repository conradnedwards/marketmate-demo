MARKETMATE HOSTED DEMO

PURPOSE
This is the public evaluation/sandbox build of MarketMate. It is NOT the paid customer build.

BEFORE UPLOADING
1. Open index.html in a text editor.
2. Replace every occurrence of:
   https://www.etsy.com/listing/REPLACE-WITH-LISTING-ID
   with the final MarketMate Etsy listing URL.
3. Upload index.html to the root of the MarketMate demo subdomain.

RECOMMENDED URL
marketmate.yourdomain.com

DEMO BEHAVIOUR
- Starts with fictional Willow & Field Studio data.
- Uses sessionStorage under its own isolated key.
- Different visitors do not share browser state.
- Closing the browser session discards the working demo state.
- Reset Demo restores the original sample data.
- Backup, restore, CSV import and CSV export are disabled.
- Product and event creation are capped to keep the public demo small.
- A Content Security Policy blocks outbound script/data connections.
- No account, server database or API is used.

IMPORTANT
The demo is client-side HTML/JavaScript. Like any client-side website, its delivered code can be inspected by visitors. The protection comes from hosting a reduced demo build rather than the full paid build. Do not put secrets, licence keys, private APIs or production-only assets in this file.

OPTIONAL HOST HARDENING
If your host supports a _headers file (for example Cloudflare Pages or Netlify), upload the included _headers file as well.
