# Two independent Render projects
1. Create two empty GitHub repositories: `laser-frontend` and `laser-backend` (suggested names).
2. Open each repository's MAIN/root folder. Upload the CONTENTS of the matching extracted folder. Do not upload the enclosing folder or ZIP. Backend root must show manage.py; frontend root must show package.json.
3. Create a Render Python Web Service for backend using its README. Add Google Sheet configuration and OAuth Secret File directly in Render.
4. Create a Render Static Site for frontend, setting NEXT_PUBLIC_API_URL to the actual backend origin before building.
5. Set backend CORS_ALLOWED_ORIGINS to the actual frontend origin, then redeploy backend. Multiple origins can be comma-separated; never use a wildcard.
6. Check /api/status/, the catalogue, images and a fictional test quote. Links in both projects still use the original business contact details.

Neither repository has been created or pushed and neither service has been deployed by this package.
