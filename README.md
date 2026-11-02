# bungalow.games

Bungalow Studios' site, served by GitHub Pages at https://bungalow.games.

- `turbotide/index.html`: TurboTide's one-link page at https://bungalow.games/turbotide (the address in the TikTok and Instagram bios). Each bio links with its own tag (`?s=tiktok`, `?s=ig`) and the page hands the visitor a store link carrying that tag, so App Store Connect, Play Console and Steamworks report downloads by source. Without a tag the page recognises Instagram's and TikTok's in-app browsers (user agent, referrer), so the bios can carry the plain address. Constants at the top of its script: `PT` (Apple provider token, set), `NAMES` (tag to campaign name: tiktok, instagram, bungalow_page), `PLAY` (Play listing URL), `STEAM` (Steam page URL).
- `turbotide/water_tall.mp4` (phones and square windows: the App Store header shot's logo region on top, blended into logo-free water from the same shot below, 720x1451) and `water_wide.mp4` (wide windows: the header shot itself at 1600x686), with a `_poster.jpg` each; both 5.2 s seamless loops, 30 fps, about 2.3 MB. Cut from `/mnt/project-files/app-store-header/video/turbotide_header_video_21x9.mp4`. The water is fixed behind the whole page; the logo on the page is the one in the video.
- `index.html` (root): sends visitors to `/turbotide/`, keeping the `?s=` tag. It becomes the studio page when a second game arrives (each game in its own folder).
- `CNAME`: the custom domain for GitHub Pages. Keep it.
