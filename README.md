# bungalow.games

Bungalow Studios' site, served by GitHub Pages at https://bungalow.games.

- `index.html`: TurboTide's one-link page (the address in the TikTok and Instagram bios). Each bio links with its own tag (`?s=tiktok`, `?s=ig`) and the page hands the visitor a store link carrying that tag, so App Store Connect, Play Console and Steamworks report downloads by source. Constants at the top of its script: `PT` (Apple provider token), `PLAY` (Play listing URL), `STEAM` (Steam page URL).
- `CNAME`: the custom domain for GitHub Pages. Keep it.
- When a second game arrives, the root becomes the studio page and each game moves to its own folder (`/turbotide`, ...).
