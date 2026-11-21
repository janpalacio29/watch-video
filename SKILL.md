---
name: watch-video
description: Use when the user types /watch-video to watch an Instagram Reel or video post. Use the linked or clearly referenced video, or ask for its link. By default, briefly summarize what happens. Also handle requested downloads, timestamped shot breakdowns, and reference frames.
---

Open the supplied Instagram permalink in the connected browser. Reuse the matching tab or the user's authorized session when available. For carousels, select the requested slide and verify it contains a video. Keep the work scoped to the linked post.

To view, play or scrub the actual video. Inspect the opening, relevant cuts and ending, seeking more precisely for timestamp questions. Use visible player time or decoded file timestamps. For character references, inspect frames for face visibility, motion blur and occlusion. Listen or transcribe with an available audio tool before quoting speech. Identify any portions or audio you could not inspect.

To download, use the post’s Download action when offered. Otherwise use the browser's supported downloadMedia method on the uniquely matched visible video element when available. If the player uses segmented media and this fails, try an available yt-dlp executable on the public Instagram permalink in a fresh output folder. Pass the URL as a single argument after -- and use a unique output name for each carousel video. Preserve the best available source quality, audio, orientation and frame rate. Use ffmpeg to merge separate streams if needed. Avoid passing private links or credentials to third-party downloader sites.

Before delivery, open the saved file, check playback near the beginning and end and verify audio when present in the source. Return the playable file through the chat's supported attachment mechanism. For viewing-only requests, deliver the analysis or requested frame. If Instagram requires sign-in, use the user's authorized browser session. If the source remains inaccessible, explain the observed blocker and ask for the original video upload.
