# VideoExpress Cinematic Stickman Agent

An independently written browser-agent workflow for original vertical illustrated stories. It adapts the visual grammar observed in [this reference Short](https://www.youtube.com/shorts/LC8hYwUZ-kU) while using a new story and narration.

Repository: [krystianr81-dev/videoexpress-cinematic-stickman-agent](https://github.com/krystianr81-dev/videoexpress-cinematic-stickman-agent).

The starting workflow was [ai-playbooks/videoexpress-stickman-story-agent](https://github.com/ai-playbooks/videoexpress-stickman-story-agent). This package re-expresses the production approach rather than copying its prompt text. It is a prompt-and-story package, not an API integration or standalone video renderer.

## Files

- `nora-master.jpg`: accepted reusable character reference for this example.
- `SYSTEM_PROMPT.md`: paste into a browser-capable agent that can operate your signed-in VideoExpress session.
- `original-story.md`: eight-scene original production plan, narration, image prompts, motion prompts, and continuity handoffs.
- `acceptance-checklist.md`: production and delivery checks.
- `reference-analysis.md`: sampled-frame observations, storytelling analysis, and verification limits.
- `production-ledger.json`: ongoing job and asset record; pending fields are not evidence of completion.
- `scenes.json`: eight machine-readable scenes; scene prompts retain relevant style and identity, with tight inserts intentionally omitting people and wider set details.
- `production-notes.md`: actual shot corrections and known continuity/fidelity limitations.

## Intended treatment

Vertical 9:16, large cream heads, fine black stick limbs, colored costume torsos, imperfect heavy ink contours, cel shading, and detailed painted scenery. Brisk offscreen narration carries the story. The target captions are bold white, black-outlined short groups of one or two words near the lower center. The reference's exact lip-sync behavior remains unverified; this version deliberately uses narration with lip-sync disabled.

## Run

Open VideoExpress and sign in. Give the agent `SYSTEM_PROMPT.md` and this instruction:

> Create “The Quiet Clockmaker” using original-story.md. Use Vertical 9:16, an available neutral system narrator, offscreen narration, and the specified illustrated style. Complete the project, captions where supported, save, and verify an export. Preserve my existing work. Report any unavailable feature or user-only authentication step accurately.

Use only visible supported controls. Available voices, queue limits, caption tools, and export options depend on the active account and current interface. The observed integrated speech field has a 120-character limit per scene and can silently truncate text: count characters and verify the full entered text before speech generation. The revised story is 132 words in eight scenes, each below that limit. The completed example export is 40.33 seconds at 1080×1920, with eight scenes and integrated Beau Whitaker system narration. Burned-in captions were omitted at the user’s explicit request. Parallel planning can help, but only one agent should drive the production UI.

The story, voice, music, and character identity must remain original. No reference footage or audio is included. A generated narration script alone does not mean a video has been rendered.



## Completed example

**The Quiet Clockmaker** — original 132-word story, eight scenes, 40.33 seconds, vertical Full HD MP4. Saved in VideoExpress as “The Quiet Clockmaker - Cinematic Stickman Short.”

[Play or download the generated example](https://cdn-ny-b.videoexpress.ai/video/1793548423_6ae7608707724.mp4). The export was downloaded and opened successfully. See production-notes.md for the scope of visual/audio verification.
