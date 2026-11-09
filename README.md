# carra AL — foundation v0.1

This is the first installable-web-app foundation for the carra AL project.

## Included
- Responsive mobile-first interface
- Chat history stored locally in the browser
- Manual personal-memory notes stored locally
- Export local data as JSON
- Light/dark mode
- Media file picker (selection only; no AI analysis yet)
- Basic service worker for offline app shell

## Important limitations
This version is **not yet connected to an AI model**. Chat messages receive a clear placeholder response. It does not yet analyze images/videos, generate video, provide live camera conversation, sync cloud data, or authenticate multiple users.

No API key belongs in frontend files or a public GitHub repository. A later AI connection must use a server-side proxy and a provider's current free-tier limits. Never commit secrets or personal data.

## Deploy with GitHub Pages
1. Open repository Settings → Pages.
2. Under Build and deployment, select Deploy from a branch.
3. Select branch `main` and folder `/ (root)`, then Save.
4. Wait for the Pages URL to appear.

For a public repository, anyone can see source code. Do not store private data in the repository. Local browser data stays on the user's device, but may be lost if website data is cleared.
