---
trigger: always_on
---

- Stack: React Native + Expo (SDK 57), TypeScript, Expo Router. Backend later: Node/Express + Neon Postgres.
- The app name is a placeholder until the final name is chosen. Keep the display name in ONE constant (APP_NAME) in a single config file. Keep name, slug and scheme in app.json as placeholders too. Do NOT set a real Android package name or iOS bundle identifier; ask me first, because those cannot be changed after publishing.
- Never hardcode secrets, URLs or API keys. Use environment variables.
- Keep components small. Ask before adding any new library.
- Never run `npm audit fix --force` or upgrade the Expo SDK without asking.
- Explain what you changed after each task.