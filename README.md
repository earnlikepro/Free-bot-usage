# EarnLikePro — Free Bot Access

The approved EarnLikePro free bot usage landing page, with gold accents and glowing plum and lavender backgrounds.

## Files

- `dist/index.html`: page content and illustrative trading interface.
- `dist/style.css`: styling and responsive layouts.
- `dist/script.js`: automation demo play/pause and copyright year.
- `vercel.json`: static deployment configuration.

## Local preview

Run `python3 -m http.server 8000 --directory dist` and open http://localhost:8000.

## Deploy through GitHub and Vercel

Import `earnlikepro/Free-bot-usage` into Vercel. Select **Other** as the framework, leave the repository root as the root directory, use no build or install command, and set the output directory to `dist`. The included configuration sets the output directory and clean URLs. No VS Code, server runtime or environment variables are required.

## Onboarding

The approved design currently displays **Registration opening soon**. Replace that notice with the confirmed EarnLikePro onboarding destination when registration is ready. Other calls to action navigate to the setup section.

This is a static marketing page. It does not implement user authentication, accept trading credentials or connect to broker accounts. The strategy chart and animated process are illustrative.
