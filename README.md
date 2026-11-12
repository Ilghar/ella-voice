A public spec for Ella's Tehrani voice lock, multi-character routing, and visual identity, so she still sounds and looks like herself after many sessions.

Intimate and adult scene banks stay on Drive. This repo keeps the engineering: phonetics, TTS stretch, agency, tags, anti-repeat, and portrait lock.

<p align="center"><a href="https://github.com/Ilghar/ella-voice">Repository</a> · <a href="https://ilghar.studio">ilghar.studio</a></p>

## How it's used

This is a lock file, not a single prompt.

| Layer | Job |
| --- | --- |
| Voice | 21–22 Tehrani, high-girly Ara, full harakat muhaverei, stretch law |
| Router | Ela / Pegah / Navid / Kian tagged lines, one speaker per block |
| Agency | door / guest protocol — never collapse to a one-word moan |
| Visual | identity lock and anti-default (no face averaging) |
| Studio | Drive STUDIO_V6_2_1 spatial production atlas (images, not in git) |

Load order (v7.1):

1. `skills/SKILL.md` — rules of truth
2. `skills/behavior-v7.md` + `skills/voice-v7.md`
3. Deep banks on Drive (sample and recombine, never linear-read)
4. Strategy and phonetic core locks

Ignore live: Drive `_CACHE_PRE_V7/`. Skill trigger: `/ella-persian-voice`. Voice product: Ara. App export fields are in the Drive export pack.

## Sources of truth (do not flatten)

| Where | What | URL |
| --- | --- | --- |
| Drive voice pack | ELA_VOICE_v2_6-8-26 (inside Ella and Friends) | https://drive.google.com/drive/folders/10XWDV1BAyslvtd9BQ_dANtfnQzoPW8VD |
| Drive friends root | Friends root folder | https://drive.google.com/drive/folders/1zeN9-_xjuVjTeiiDm2fIe0B0Oki3ZySt |
| Drive visual finals | STUDIO_V6_2_1_RELEASE_2026-08-31 | https://drive.google.com/drive/folders/14qT0sP8CJAarIlLIgZjXBYkNtomLEi5g |
| Hugging Face | ilghar buckets (Persian TTS research) | https://huggingface.co/ilghar |
| GitHub | this spec | https://github.com/Ilghar/ella-voice |

Voice finals = Drive voice pack v7.1 (2026-08-09). Visual, camera, and spatial finals = Studio v6.2.1 (2026-08-31), not the Friends root. Do not merge the 44 MB studio zip into this git.

## Coolest-thing (TypeSafe Jev waitlist)

A skill stack that keeps a Tehrani Persian voice agent and two visual identities locked across chats: phonetic rules (harakat, stress, TTS stretch), multi-character routing, and identity-locked image prompts so faces do not average. Drive is the source of truth; this repo is the public spec.

## Hardware note

2019 15-inch MacBook Pro, Intel i9, 32 GB, Vega 16. Local Wan 2.2 / Hunyuan were researched as optional; this repo does not assume a local video GPU.

<sub>ilghar.studio</sub>
