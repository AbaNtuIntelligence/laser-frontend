# Laser showcase frontend
Standalone Next.js static export. Upload the contents of this folder into a new frontend repository.

Render: Static Site; root directory blank; build `npm ci && npm run build`; publish `out`.
Set `NODE_VERSION=24.19.0` and `NEXT_PUBLIC_API_URL` to the actual backend HTTPS origin, with no trailing slash and no `/api` suffix, BEFORE building. Rebuild after changing this variable.
The backend CORS_ALLOWED_ORIGINS must include this site's exact HTTPS origin.

Local development: `npm ci`, copy `.env.example` to `.env.local`, set the API URL, then `npm run dev`.
The contact and WhatsApp links remain the original business links. Quote submission uses the selected backend.
