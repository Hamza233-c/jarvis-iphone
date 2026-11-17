JARVIS iPhone PWA prototype

Files:
- index.html: app interface and logic
- manifest.webmanifest: installable web app metadata
- sw.js: offline app-shell cache
- icon.svg: app icon

Run/deploy:
Host these files on an HTTPS static host (for example GitHub Pages). Open the HTTPS URL in Safari on iPhone, tap Share, then Add to Home Screen.

Offline mode includes limited built-in commands. For open-ended AI, configure an OpenAI-compatible endpoint, model and API key from a provider with a free tier. Provider availability, usage limits, API compatibility and browser CORS support vary. The key is stored in browser localStorage and requests are sent directly from the device to the provider. For a production app, use a secured backend/proxy instead of exposing API keys in a client app.

This is a progressive web app prototype, not a native App Store app and not a direct installation of Stanford OpenJarvis. It is designed as an iPhone-friendly frontend inspired by the project.
