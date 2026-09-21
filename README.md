# Kids TV – panel rodzica

Web page for managing the Kids TV app's approved channels, playlists and single videos from a phone.

- Contains **no keys or account data**. On first use it asks for a GitHub token (Gists: read & write) and a YouTube Data API key; both are stored only in that browser's local storage.
- Talks only to `api.github.com` and `www.googleapis.com` (enforced by its Content-Security-Policy).
- Source of truth is the private project repository; this repo only hosts the page.
