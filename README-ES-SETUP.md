# 🇪🇸 Sherlock Holmes — SPANISH Adaptation Project — Setup Guide

The deployable **Claude Project** for converting finished, polished English
Sherlock scripts into **native-quality Spanish (Castellano literario)
TTS-ready scripts** — plus Spanish titles, description, tags, and a quiz.

Register anchor: the classic Peninsular Spanish translations of Conan Doyle
— supra-regional literary Spanish with Castilian defaults, so Spain is
served first (the CPM decision) without alienating Latin American
listeners. Carries every lesson from the French and German audits (v1.1:
structural calques, pair-specific idiom maps, calibrated period forms).

---

## 📁 What's in this package

```
sherlock-spanish/
├── README-ES-SETUP.md                  ← this file
├── ES-CLAUDE-PROJECT-INSTRUCTIONS.md   ← paste into "Custom Instructions"
└── knowledge/                          ← upload ALL 4 to Project Knowledge
    ├── ES-01-LINGUISTIC-RULES.md       ← usted, rayas, falsos amigos, calques…
    ├── ES-02-STYLE-SAMPLE.md           ← the Spanish VOICE anchor
    ├── ES-03-TTS-RULES.md              ← Spanish AI-voiceover writing rules
    └── ES-04-LOCKED-GLOSSARY.md        ← names/places locked + series voices
```

## 🛠️ Setup (5 minutes)

1. claude.ai → Projects → **+ Create Project**
2. Name it: **"Sherlock — Adaptación Española"**
3. **Set Custom Instructions** → paste ALL of
   `ES-CLAUDE-PROJECT-INSTRUCTIONS.md`. Save.
4. **Project Knowledge → Add Content** → upload the 4 ES files.
5. Done.

## ▶️ Per-episode usage (identical to FR/DE workflow)

1. **FRESH chat** → paste the **final polished English script**.
2. Claude replies: one-line part plan + **PART 1** (pure Spanish between
   copy-markers).
3. **"next"** → next part. Final part comes with **3–4 TÍTULOS +
   DESCRIPCIÓN + 10–12 TAGS + 1 QUIZ**, each with a one-line English gloss.

## 🎙️ One decision that lives OUTSIDE the script: the VOICE accent
The script is supra-regional literary Spanish — it reads correctly in
Madrid and in Mexico City. The **accent signal comes from the TTS voice you
pick** (Castilian distinción vs Latin seseo), not from the text. Default
assumption: a Castilian voice (matches the Spain-first CPM strategy). Pick
it consciously and keep it consistent across episodes.

## ⚠️ One-time calibration (Episode 1 — do not skip)

Send ~1,500 words of the Spanish output to a **native Spanish reviewer
(Spain)** (Fiverr, $20–50): *"Does this read like it was originally
written in Spanish, in the register of a classic Sherlock Holmes
translation? Flag any unnatural phrasing, Anglicisms, or dequeísmo."* Feed
corrections back → codify as new rules in the ES files.

## 📏 Part math

Spanish runs ≈ **1.15–1.25×** English (sometimes up to 1.30 — normal,
good). Parts stay at **3,500–4,500 Spanish words**, cut only at chapter
boundaries. Claude announces the plan before Part 1.

## 🔒 Three Spanish-specific guarantees

1. **La raya, not quotation marks** — Spanish dialogue uses the dash
   (—Deténgase —dijo Holmes.), with correct incise mechanics, hard-enforced.
2. **Usted everywhere; opening ¿ and ¡ never forgotten** — both are
   top AI-slip points and both are QC-checked on every part.
3. **The Bell → „La Campana"**, and Holmes files the card under the letter
   **C** — the index letter follows the Spanish name (same logic as
   French B→C, German B→G).
