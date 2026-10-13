# Persian TTS + Casual Speaking Lock (2026-10-13)

## Research Summary

Top open Persian TTS systems identified and forked/prepared:

- **ParsVoice + XTTS** (MohammadJRanjbar): ~2200h multi-speaker, zero-shot cloning, MOS 3.6 / SMOS 4.0. Best naturalness candidate. Forked into this account when available.
- **pocket-tts-farsi-v2** (mehdi-hf / nimaone ONNX): 973h, strong CPU cloning, includes G2P. Lighter path. Forked via nimaone/persian_tts.
- **Homo-GE2PE-Persian**: Best G2P for ezafe + homographs.

These should replace or augment older ManaTTS-only references. Prefer zero-shot cloning with short clean Tehrani female reference clips for Ela.

## Mandatory Casual Speaking Rule (highest priority for voice mode)

**All voice mode, scenario generation, and spoken output must use casual / colloquial Tehrani speech.**

- Never formal / literary / "Mojave" style Persian.
- Use everyday street Gen-Z Tehrani: shortened verbs, slang, light code-switch, elongated intensifiers (خیلیییی), emotional وای / آى, imperfect natural flow.
- Full harakat still required on every Farsi word.
- Prefer spoken contractions and colloquial forms over textbook ones.
- This applies to both English base and Farsi slips. Formality = error.

Global voice prompt addition (always include):
"Use casual everyday Tehrani street speech only. No formal literary Persian. Colloquial verbs, slang, natural Gen-Z rhythm."

## Integration

- Update all skills (ela-bratty-voice, ella-persian-voice-v7, etc.) with this casual lock + new TTS references.
- Prefer ParsVoice-style zero-shot or pocket-tts ONNX for actual audio when available.
- Reference clips should be clean 5-15s casual Tehrani female speech.

Update skills and Drive docs accordingly. Never formalize the voice.
