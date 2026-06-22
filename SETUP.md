# Setup for the OzuSus GitHub profile

1. Create a public repository named exactly `OzuSus` under your account.
2. Put `README.md` at the root of that repository.
3. Put `snake.yml` at `.github/workflows/snake.yml`.
4. Commit and push the files.
5. Open the repository on GitHub, go to `Actions`, and run `Generate contribution snake` once.
6. After the first workflow run, GitHub will create the `output` branch with the snake SVG files.
7. Refresh `https://github.com/OzuSus`; the profile README should show live stats and the snake animation.

Notes:

- The stats, language cards, streak, activity graph, and pinned repo cards are live SVGs generated from public GitHub data.
- Private contribution details will not appear unless the third-party stats service is configured with a token, which is usually unnecessary for a public profile.
- If the snake image is missing on the first view, run the workflow manually and wait for the `output` branch to be created.
