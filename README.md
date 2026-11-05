# interactive-film-pipeline

A Claude Code skill for building **AI interactive films** (branching-story video games): from premise and script, through the art & sound bible, AI image/video/voice production, a web demo used as the debugging environment, review-and-rework loops, 1080p masters, to Unity packaging and Steam launch prep.

It is distilled from a real two-day production (《敕勒川》: 111 scenes, 171 choices, 36 deaths, 11 endings, ~85 minutes of footage), including every rework it took, so the pitfalls come with root causes and the fix to apply next time.

Content is in Chinese.

## Contents

| File | Stage |
|---|---|
| `SKILL.md` | Stage map, gates, ten hard rules, routine for each push |
| `references/01-design.md` | Premise, branch types, flags, pacing curve, memes, history |
| `references/02-bible.md` | Visual and voice rules, POV / narration ratio |
| `references/03-production.md` | Keyframes → video → voice → segmented cuts |
| `references/04-web-demo.md` | Data-driven web engine, path checker, merging, publishing |
| `references/05-review-rework.md` | Review rounds, zero-reshoot fix tiers, rework catalogue |
| `references/06-hd-master.md` | 1080p masters that reuse everything but the video |
| `references/07-release.md` | Unity (final build only) and Steam launch prep |
| `references/08-orchestration.md` | Running many Claude sessions in parallel safely |
| `references/lessons-log.md` | Dated lessons, appended as projects run |

## Install

```bash
git clone https://github.com/jasoncai0/interactive-film-pipeline ~/.claude/skills/interactive-film-pipeline
```

The tool-specific parts reference the libtv canvas CLI (Lib Image / Seedance / Minimax TTS); the stages, gates and lessons apply to any generation stack.

## License

MIT
