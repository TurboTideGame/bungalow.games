# bungalow.games

Bungalow Studios' site, served by GitHub Pages at https://bungalow.games.

- `turbotide/index.html`: TurboTide's one-link page at https://bungalow.games/turbotide (the address in the TikTok and Instagram bios). Each bio links with its own tag (`?s=tiktok`, `?s=ig`) and the page hands the visitor a store link carrying that tag, so App Store Connect, Play Console and Steamworks report downloads by source. Without a tag the page recognises Instagram's and TikTok's in-app browsers (user agent, referrer), so the bios can carry the plain address. Constants at the top of its script: `PT` (Apple provider token, set), `NAMES` (tag to campaign name: tiktok, instagram, bungalow_page), `PLAY` (Play listing URL), `STEAM` (Steam page URL).
- `turbotide/water_loop.mp4` and `water_poster.jpg`: the water band at the top, the App Store header's 5.2 s seamless loop (`/mnt/project-files/app-store-header/video/turbotide_header_video_21x9.mp4`) at 1600x686, 30 fps, 2.5 MB. The logo on the page is the one in the video; the band's height (`--hero`) sets its size.
- `index.html` (root): sends visitors to `/turbotide/`, keeping the `?s=` tag. It becomes the studio page when a second game arrives (each game in its own folder).
- `CNAME`: the custom domain for GitHub Pages. Keep it.
