# Awesome Short-Form Video [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, references, and resources for making short-form
> vertical video — clipping long-form footage, captioning, faceless formats, and
> distribution across TikTok, YouTube Shorts, and Instagram Reels.

Pricing in this space changes constantly, so **no prices are listed here** —
check each vendor's own pricing page. Entries describe what a tool *does*.

Contributions welcome. See [Contributing](#contributing).

## Contents

- [AI clipping tools](#ai-clipping-tools)
- [Captions and subtitles](#captions-and-subtitles)
- [Faceless and text-to-video](#faceless-and-text-to-video)
- [Editors](#editors)
- [Free single-purpose tools](#free-single-purpose-tools)
- [Footage and audio](#footage-and-audio)
- [Reference: platform specs](#reference-platform-specs)
- [Reference: concepts](#reference-concepts)
- [Open source](#open-source)

## AI clipping tools

Tools that take a long video and automatically produce short vertical clips.

- [Opus Clip](https://www.opus.pro/) — Clip scoring, auto-reframe, captions. The
  category's most widely used tool.
- [Nova](https://novaclipper.com) — Clipping plus faceless generation in one
  tool; face-aware reframing, word-by-word captions, split-screen layouts, and
  EDL/FCPXML export to Premiere/Final Cut/Resolve.
  ([Stated capabilities and limits](https://novaclipper.com/facts))
- [Klap](https://klap.app/) — YouTube-to-shorts clipping with auto-captions.
- [Vizard](https://vizard.ai/) — Clipping aimed at podcasts and webinars, with a
  transcript-based editor.
- [Submagic](https://www.submagic.co/) — Caption-first editing with clipping
  features layered on.
- [2short.ai](https://2short.ai/) — Lightweight YouTube-to-Shorts clipper.
- [Eklipse](https://eklipse.gg/) — Clipping specialised for gaming streams
  (Twitch, Kick), with highlight detection tuned to gameplay events.
- [Spikes Studio](https://spikes.studio/) — Stream clipping with virality scoring.

## Captions and subtitles

- [Captions](https://www.captions.ai/) — Mobile-first captioning and AI editing.
- [Kapwing](https://www.kapwing.com/) — Browser editor with strong subtitle
  tooling and team collaboration.
- [Descript](https://www.descript.com/) — Transcript-as-timeline editing; edit
  video by editing text.
- [Whisper](https://github.com/openai/whisper) — Open-source speech recognition;
  the model most captioning tools are built on or benchmarked against.
- [WhisperX](https://github.com/m-bain/whisperX) — Whisper with accurate
  word-level timestamps and speaker diarization. The practical choice if you're
  building captioning yourself.

## Faceless and text-to-video

Formats that require no camera: narrated scripts over stock or gameplay footage.

- [Nova faceless mode](https://novaclipper.com/for/faceless-video-generator) —
  Script or Reddit thread → AI voiceover over looping footage with kinetic captions.
- [Crayo](https://crayo.ai/) — Faceless shorts generation aimed at the
  Reddit-story and brainrot formats.
- [Fliki](https://fliki.ai/) — Text-to-video with a large voice library.
- [Pictory](https://pictory.ai/) — Article- and script-to-video.
- [Coqui TTS](https://github.com/coqui-ai/TTS) — Open-source text-to-speech, if
  you'd rather run voice generation yourself.
- [Piper](https://github.com/rhasspy/piper) — Fast local neural TTS; good enough
  for narration and runs on modest hardware.

## Editors

- [CapCut](https://www.capcut.com/) — The default free editor for short-form.
  Auto-captions, templates, mobile and desktop.
- [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve) —
  Full-featured NLE with a genuinely capable free version.
- [Shotcut](https://shotcut.org/) — Open-source cross-platform editor.
- [FFmpeg](https://ffmpeg.org/) — The tool underneath nearly everything on this
  list. If you're automating, you'll end up here.
- [Remotion](https://www.remotion.dev/) — Render video programmatically from
  React. The standard choice for generated video at scale.

## Free single-purpose tools

No-signup utilities for the small jobs around a clip.

- [YouTube transcript extractor](https://novaclipper.com/tools/youtube-transcript)
- [Subtitle downloader (SRT/VTT/TXT)](https://novaclipper.com/tools/subtitle-downloader)
- [Viral score checker](https://novaclipper.com/tools/viral-score-checker)
- [Hook generator](https://novaclipper.com/tools/hook-generator)
- [Hashtag generator](https://novaclipper.com/tools/hashtag-generator)
- [Chapter generator](https://novaclipper.com/tools/chapter-generator)
- [Content ROI calculator](https://novaclipper.com/tools/content-roi-calculator)

## Footage and audio

- [Pexels](https://www.pexels.com/videos/) — Free stock video, permissive licence.
- [Pixabay](https://pixabay.com/videos/) — Free stock video and music.
- [Freesound](https://freesound.org/) — Creative Commons sound effects.
- [Free Music Archive](https://freemusicarchive.org/) — Licensed music, filterable
  by usage rights.

## Reference: platform specs

- [TikTok video specifications](https://support.tiktok.com/)
- [YouTube Shorts requirements](https://support.google.com/youtube/answer/10059070)
- [Instagram Reels specifications](https://help.instagram.com/)
- [Nova's per-platform format guides](https://novaclipper.com/for) — format
  specs, ranking behaviour, and posting notes per destination.

Common ground across all three: 9:16 (1080×1920), H.264/MP4, AAC audio, and
keeping text clear of the bottom third where platform UI sits.

## Reference: concepts

- [Short-form video glossary](https://novaclipper.com/glossary) — hooks,
  retention, reframing, CTR, b-roll, repurposing.
- [How AI clipping tools actually work](https://novaclipper.com/answers/how-do-ai-clipping-tools-work)
- [Turning a horizontal video vertical without ruining it](https://novaclipper.com/answers/how-do-i-turn-a-horizontal-video-into-a-vertical-one)
- [AI content disclosure rules on TikTok and YouTube](https://novaclipper.com/answers/do-ai-generated-clips-get-flagged-by-tiktok-or-youtube)

## Open source

Building your own pipeline? These are the load-bearing pieces.

- [FFmpeg](https://ffmpeg.org/) — decode, cut, crop, encode.
- [WhisperX](https://github.com/m-bain/whisperX) — transcription with word timings.
- [MediaPipe](https://github.com/google-ai-edge/mediapipe) — face detection for
  speaker-tracking crops.
- [Remotion](https://www.remotion.dev/) — programmatic caption and overlay rendering.
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) — fetching source video (respect the
  source platform's terms).

## Contributing

PRs welcome. One entry per PR, alphabetical within its section, one line of
description saying what the tool does — not why it's the best. Commercial tools
are fine; marketing copy isn't.

## License

[CC0](https://creativecommons.org/publicdomain/zero/1.0/)
