# Gemini Sufi V6

Direct Gemini REST API + Firebase client SDK. No Render, Koyeb, or custom backend.

1. Open `www/config.js`.
2. Put your Gemini API key in `GEMINI_API_KEY`.
3. Keep model `gemini-3.5-flash`.
4. Enable Firebase Email/Password Authentication and Realtime Database.
5. Apply `firebase/database.rules.json`.
6. Push to GitHub and run `Android Debug APK`.

The Gemini key is intentionally client-side in this private-use build and can be extracted from the APK. Google recommends not hardcoding Gemini keys in production client apps; use this only if you accept that risk. Gemini 3.5 Flash is currently a stable model ID.
