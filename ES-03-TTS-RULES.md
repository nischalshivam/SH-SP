# ES-03 — TTS / AI-NARRATION RULES, SPANISH (Knowledge File)

The Spanish script is read by an **AI voice**. Every part must obey these
rules — the Spanish fork of the master system's file 14. They **override
literary/typographic habit wherever the two conflict** (e.g. semicolons).

---

## 1. PUNCTUATION = PACING
- **Coma** = short breath. Shape rhythm with commas.
- **Punto** = full stop. Prefer **short-to-medium sentences**; Spanish can
  run long and musical, but the narrator still needs air — don't let a
  sentence outlast one breath.
- **Raya (—)** = dialogue marker (ES-01 §4) AND, mid-sentence, a sharp
  aside. Context distinguishes them; keep dialogue rayas at line start.
- **Puntos suspensivos (…)** = trailing, hesitant pause. Sparing.
- **Paragraph break** = longer beat. Break often — audio needs air.
- **Semicolons: BANNED.** Use a full stop.

## 2. ¿ AND ¡ — OPENING MARKS ARE MANDATORY ⭐ (TTS-critical)
Every question and exclamation carries **both** marks — opening and closing:
*¿Quién anda ahí? · ¡Deténgase! · ¿No lo ve usted?*
- The opening **¿ / ¡** tells the TTS engine to build the interrogative or
  exclamatory intonation **from the start of the phrase**. Without it, the
  voice reads flat and only "realizes" at the end — the single most common
  Spanish TTS failure.
- Applies in narration AND dialogue, in titles, everywhere.
- For a question embedded mid-sentence, place the ¿ exactly where the
  question begins: *Y entonces, ¿qué vio usted?*

## 3. NUMBERS, DATES, TIMES, MONEY — always spelled out in Spanish words
| Written form | ✓ In narration |
|---|---|
| 1884 | **mil ochocientos ochenta y cuatro** |
| 9:30 | **las nueve y media** |
| 9:15 | **las nueve y cuarto** |
| 9:45 | **las diez menos cuarto** |
| March 23rd | **el veintitrés de marzo** |
| £3 10s | **tres libras y diez chelines** |
| a half-crown | **media corona** |
| 5 guineas | **cinco guineas** |
| 7% | **el siete por ciento** |
| 221B Baker Street | **el doscientos veintiuno B de Baker Street** |

- Time uses **las** + hour (*a las diez, cerca de las diez*); never "10:05".
- Imperial units keep the Victorian illusion: **millas, pies, pulgadas,
  yardas** — never kilómetros/metros.

## 4. ABBREVIATIONS — none in spoken text
Write in full: **señor, señora, señorita, doctor, san** (never Sr., Sra.,
Srta., Dr., S.). "Cox & Co." → rephrase (**el banco Cox, en Charing
Cross**). The symbols **& % §** never appear in narration.

## 5. ROMAN NUMERALS — never
Rephrase: not «Eduardo VII», but **«el rey Eduardo»** (or spell the ordinal
if essential). Chapter headings spelled out (§8).

## 6. ACCENTS ARE MEANING — never drop them (TTS-critical)
A missing or wrong accent can flip the word the engine reads:
- **tú** (you) / **tu** (your) · **él** (he) / **el** (the) · **sí** (yes) /
  **si** (if) · **sé** (I know) / **se** (reflexive) · **más** (more) /
  **mas** (but) · **té** (tea) / **te** (you-obj) · **dé** (give) / **de**
  (of) · **aún** (still) / **aun** (even).
- Homograph stress pairs to watch: **está/esta**, **hablo/habló**,
  **ingles/inglés**, **papa/papá**, **secretaria/secretaría**. Ensure the
  accent matches the intended word so the stress lands correctly aloud.

## 7. FOREIGN NAMES & ORTHOGRAPHY
- English names are pronounced with a Spanish accent by the voice — **that
  is correct**; a native Spanish narrator says «Sherlock Holmes», «Baker
  Street» exactly so. Never respell phonetically.
- Keep standard modern Spanish orthography (post-2010 RAE): no accent on
  *solo/este* unless you deliberately keep the traditional *sólo* — if so,
  be consistent.

## 8. CHAPTER HEADINGS — voiced, minimal, spelled out
Classic style: **«Capítulo primero», «Capítulo segundo», «Capítulo
tercero» …** (ordinals up to ~décimo; beyond, cardinals: «Capítulo once»).
Optionally a title after a colon (*Capítulo tercero: La campanilla de
latón*). Own line, blank line after. The English "Cold Open" heading
becomes **«Prólogo»**.

## 9. DIALOGUE FOR THE EAR
- La raya per ES-01 §4; new paragraph per speaker; action beats on their
  own paragraph.
- Re-anchor the speaker by name every few lines (*replicó Holmes*) — the
  ear cannot glance back up the page.
- Tags simple and lowercase; the voice carries emotion, not adverbs. For
  emphasis, **rephrase** — TTS ignores italics.
- Every ¿?/¡! inside dialogue carries both marks (§2).

## 10. CLARITY HABITS
- One idea per sentence in tense moments; avoid runaway subordination.
- No bracketed tags of any kind inside output (no SFX, no notes) — clean
  voice-ready text only.
- Read-aloud test: if a human would stumble, the AI will too.

---

## QUICK CHECK (run silently before delivering every part)
- [ ] No raw numerals, years, symbols, or abbreviations in spoken lines
- [ ] **Opening ¿ and ¡ present on every question/exclamation**
- [ ] No semicolons; no sentence longer than one breath
- [ ] Headings «Capítulo primero …» spelled out; «Prólogo» for the cold open
- [ ] La raya dialogue, lowercase tags, action beats on own lines
- [ ] Meaning-accents correct (tú/tu, él/el, sí/si, sé/se, más/mas)
- [ ] No phonetic respelling of English names
- [ ] Reads aloud smoothly, with the dignity of a classic translation
