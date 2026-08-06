PIPE PILOT MERCH V2 — SANDBOX

Open merch.html directly for a quick preview. The page contains fallback product data, so it works even when your browser blocks products.json under file://.

For the cleanest test, run a local server from this folder:
  python -m http.server 8000
Then open:
  http://localhost:8000/merch.html

Current milestone:
- Product catalogue driven by products.json
- Permanent PP-001 / PP-002 / PP-003 SKUs
- Edition and release-date fields
- Stock and units-sold fields
- Stock-state labels
- Mock Add to Cart counter
- Retired collection foundation

Not yet connected:
- Cart drawer and quantity controls
- Stripe Checkout Sessions
- Shared inventory database
- Webhooks
- Admin controls
