# bungalow.games

Bungalow Studios' site, served by GitHub Pages at https://bungalow.games.

- `turbotide/index.html`: TurboTide's one-link page at https://bungalow.games/turbotide (the address in the TikTok and Instagram bios). Each bio links with its own tag (`?s=tiktok`, `?s=ig`) and the page hands the visitor a store link carrying that tag, so App Store Connect, Play Console and Steamworks report downloads by source. Constants at the top of its script: `PT` (Apple provider token), `PLAY` (Play listing URL), `STEAM` (Steam page URL).
- `turbotide/water_loop.mp4` and `water_poster.jpg`: the page's background, a 5 s loop cut from the end card's logo-on-water shot (`/mnt/project-files/marketing-video/capture-hacks/logo_on_water_textfree.mp4`, 3.6 s to 9.6 s, crossfaded into itself; 720x1280, 30 fps, 1.4 MB). The logo on the page is the one in the video.
- `index.html` (root): sends visitors to `/turbotide/`, keeping the `?s=` tag. It becomes the studio page when a second game arrives (each game in its own folder).
- `CNAME`: the custom domain for GitHub Pages. Keep it.
