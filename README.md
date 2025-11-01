# Fluxfeed API Docs

Static one-page docs for `docs.fluxfeed.news`.

- Live API: `https://api.fluxfeed.news`
- OpenAPI: `https://api.fluxfeed.news/openapi.json`
- CORS is enabled for this origin.

## Deploy (Vercel)
1. New Project → import this folder.
2. Add custom domain: `docs.fluxfeed.news`.
3. In Namecheap DNS: `CNAME docs → cname.vercel-dns.com` (or the value Vercel shows).
4. Redeploy if needed.

## Smoke tests
- Load the site and ensure:
  - Status pill says **Operational**.
  - Redoc renders endpoints from the live spec.
