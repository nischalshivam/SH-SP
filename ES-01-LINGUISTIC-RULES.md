# ES-01 — LINGUISTIC RULES (Knowledge File) — v1.1-native
(Built with the French + German audit lessons pre-installed: structural
calques §6, pair-specific idiom maps, calibrated period forms, frame-tense
nuance.)

The grammar and register laws that make the Spanish output read as
**natively written**, in the register of classic Peninsular Spanish
(Castellano) Conan Doyle translations. Checked in the internal QC pass
before every part.

---

## 0. DIALECT: CASTELLANO LITERARIO (supra-regional, Castilian default)
Write **high-literary Peninsular Spanish** — the register of the classic
Spanish Doyle translations. In practice this is largely **supra-regional**:
correct literary Spanish reads well in Madrid and in Mexico City alike. The
Castilian defaults we DO lock:
- **Vocabulary:** *coche/coche de punto* over *carro*; *cerillas* over
  *fósforos* where it occurs; *aparcar* never (period anyway).
- **NO voseo** (no *vos/tenés*) — usted/tú only.
- **Vosotros:** avoid in narration; it can appear only if a character
  addresses a group informally (rare — mostly children). Default plural
  address between adults is **ustedes** contexts handled via usted.
- The **accent** (distinción vs seseo, vosotros vs ustedes in speech) is
  ultimately carried by the TTS VOICE, not forced into the text. Keep the
  text supra-regional; let the Castilian voice do the rest.

## 1. LOS TIEMPOS DEL PASADO (the literary past system)
Narration runs on the two literary pasts, correctly balanced:
- **Pretérito indefinido** for the chain of completed events: *entró,
  encendió la pipa, se volvió, dijo, cayó.*
- **Pretérito imperfecto** for description, background, ongoing states,
  habit: *llovía contra los cristales, llevaba un abrigo gris, sostenía los
  guantes, la casa aún dormía.*
- **Pluscuamperfecto** for backstory: *no había tocado el desayuno.*
- AI tends to over-use one past tense (an Anglo reflex). The
  indefinido/imperfecto interplay is what makes Spanish narration breathe;
  get it right sentence by sentence.
- **Watson's present-frame commentary** (writing from "now": *«Lo he
  guardado, doblado junto al mapa»*) correctly uses pretérito perfecto /
  presente. Frame = perfecto/presente; story = indefinido/imperfecto. (In
  Peninsular Spanish the pretérito perfecto — *he hablado* — is alive and
  correct for the frame; do not replace it with indefinido there.)

## 2. USTED — ABSOLUTE
All adults of the era address each other as **usted** — Holmes and Watson
included, after decades of friendship. Clients, police, suspects, servants:
usted, always. **Tú is forbidden** except an adult addressing a child
(Baker Street irregulars). Everything must agree: **usted, su, le, lo/la,
consigo** — a stray *tú / tu / te / tuyo / contigo* is an instant register
break that makes the pair sound like teenagers.

## 3. LA MUSICALIDAD / EL FLUJO (foisonnement, Spanish edition)
Spanish runs ≈ **15–25% longer** than English (occasionally 30%). Do NOT
compress to match English sentence lengths — forced compression produces
choppy, unnatural Spanish. Let sentences flow to the language's syllable-
timed, musical rhythm. BUT: the expansion must come from **Spanish
syntax**, never from added content, invented atmosphere, or padding.

## 4. LA RAYA DE DIÁLOGO — dialogue mechanics (NOT English quotes) ⭐
Spanish dialogue uses **la raya (—)**, never « » or " " on spoken lines.
The mechanics are precise (get them exactly right — this is the #1
typographic tell):
- **Raya glued to the first spoken word**, no space: *—Deténgase.*
- When a **verbo de habla** (dijo, preguntó…) follows the line, open a
  second raya glued to the speech, and the tag is **lowercase**:
  *—Deténgase —dijo Holmes.*
- If the speech continues after the tag, close with a raya:
  *—Deténgase —dijo Holmes— y no toque nada.*
- If the tag is NOT a verb of speech (an action), the sentence before it
  ends with a period, and the action is capitalized on its own:
  *—Deténgase. —Se volvió hacia la ventana.* → prefer putting a pure action
  beat on **its own paragraph without a raya** (cleaner for TTS).
- Punctuation of the line goes **before** the closing raya/period per the
  rules above; commas/periods sit correctly against the raya.
- New paragraph per speaker; re-anchor the speaker by name every few lines
  in long exchanges (the ear cannot glance back).

## 5. VERBA DICENDI — variety is mandatory
In Spanish literature, repeating *dijo* reads as poor writing (unlike
English, where "said" is invisible). Rotate a rich set — period-apt:
*repuso, replicó, contestó, respondió, murmuró, susurró, observó, preguntó,
inquirió, exclamó, objetó, sentenció, añadió, prosiguió, continuó, gruñó,
terció, admitió, concedió.* Keep tags lean — the voice carries emotion, not
piled-up adverbs.

## 6. CALCOS ESTRUCTURALES — English skeletons under Spanish words ⭐
The deepest failure layer (proven by the French Episode 1 audit). Every
word Spanish, grammar correct — but the sentence's SKELETON is English.
Sweep for these patterns:

| English skeleton | ❌ Calque | ✓ Native rebuild |
|---|---|---|
| "was standing / was watching" | estaba siendo / estaba parado toda… | **estaba de pie** / permanecía inmóvil / observaba |
| "his hand was trembling" | su mano temblaba | **le temblaba la mano** (drop the possessive) |
| "make a decision" | hacer una decisión | **tomar una decisión** |
| "ask a question" | hacer una pregunta ✓ (this one IS hacer) | **hacer una pregunta** |
| "take an oath" | tomar un juramento | **prestar juramento** |
| "There is nothing in that." | No hay nada en eso. | **Eso no tiene nada de particular.** / No es nada extraño. |
| "money on his life" | dinero sobre su vida | **un seguro de vida** |
| "no deceit in him" (traits) | no hay engaño en él | **no hay en él doblez / malicia alguna** |

Rules behind the table:
- **Body parts drop the possessive** and take the indirect object: *le
  brillaban los ojos, se llevó la mano al sombrero* — never "sus ojos
  brillaban" as an Anglo reflex.
- **Light-verb collocations are fixed:** *tomar una decisión, prestar
  juramento/atención, hacer una pregunta, cometer un error, guardar
  silencio, dar un paseo.*
- **Spanish has no English-style progressive** for states — never build one
  where a simple tense is right.
- **⚠️ Calque maps are language-PAIR-specific.** Do NOT import French or
  German fixes wholesale — judge each idiom against SPANISH usage.
- **THE STRUCTURE TEST (every paragraph in QC):** *"Would a Spanish
  novelist have BUILT this sentence this way, or only worded it this way?"*
  If the skeleton is English, rebuild — don't re-dress.

## 7. FALSOS AMIGOS — the genre-critical killers (sweep every part)
| English | ❌ Wrong Spanish | ✓ Correct |
|---|---|---|
| evidence | la evidencia (= obviousness) | **las pruebas / los indicios** |
| bizarre | bizarro (classic = brave/gallant!) | **extraño, raro, estrambótico** |
| actually | actualmente (= currently) | **en realidad, de hecho** |
| eventually | eventualmente (= possibly) | **finalmente, con el tiempo** |
| to realize | realizar (= to carry out) | **darse cuenta, comprender** |
| sensible | sensible (= sensitive) | **sensato, prudente** |
| to introduce (sb) | introducir | **presentar** |
| to attend | atender (= to tend to) | **asistir a** |
| to pretend | pretender (= to aspire) | **fingir, aparentar** |
| sympathetic | simpático (= likeable) | **comprensivo, compasivo** |
| to assist | asistir (ambiguous) | **ayudar** (for "help") |
| a lecture | una lectura (= a reading) | **una conferencia** |
| fabric | la fábrica (= factory) | **la tela** |
| large | largo (= long) | **grande** |

Genre vocabulary: clue → **una pista / un indicio** · red herring → **una
pista falsa** · culprit → **el culpable** · witness → **el testigo / la
testigo** · landlady → **la casera / la patrona** · case → **el caso** ·
crime scene → **el lugar del crimen** · life insurance → **un seguro de
vida**.

## 8. ANGLICISMS & DEQUEÍSMO — BANNED / CONTROLLED
- **Anglicism calques:** *hacer sentido* (→ **tener sentido**) · *tomar
  acción* (→ **actuar / tomar medidas**) · *aplicar* for "apply for a job"
  (→ **solicitar**) · *remover* for "remove" (→ **quitar, retirar**;
  *remover* = to stir) · *asumir* for "assume/suppose" (→ **suponer,
  dar por sentado**) · *en orden de* (→ **para, a fin de**).
- **Dequeísmo / queísmo (precision marker):** get the *de que* boundary
  right. *Me di cuenta **de que**… · Estoy seguro **de que**… · No cabe
  duda **de que**…* BUT *Creo **que**… · Pienso **que**…* (no *de*). Errors
  here read as careless to an educated Spanish ear.

## 9. MODERN WORDS — BANNED (period ~1880–1905)
*vale (as "OK") · guay · chaval (as filler) · tío/tía (as "dude") · flipar
· móvil · gasolina · fin de semana* (as a casual anachronism). Convey
period through vocabulary, not archaism overload — "period-flavored but
accessible" applies in Spanish too.

## 10. SPANISH AI-CLICHÉ BANS
*un escalofrío le recorrió la espalda* · *las sombras danzaban* · *un
silencio ensordecedor* · *una tensión palpable* · *un tapiz de mentiras* ·
*el laberinto de mentiras* · *poco sabía él que…* · *no podía imaginar
que…* · *reluciente / etéreo* · *un testimonio de* (as "testament to") ·
*sumergirse en* as a delve-tic · *la verdad salió a la luz* as a stock
closer. Write plain, concrete, period-natural Spanish.

## 11. REGISTER BY CLASS
- **Holmes:** español culto y preciso — economía, ironía, inversión en
  preguntas (*«¿Qué deduce de ello?»*). At most one or two quiet aphorisms
  per episode.
- **Watson (narrator):** culto, cálido, modesto — ES-02 is his voice.
- **Working-class (Cobb, cocheros, servants):** short main clauses, plain
  concrete words; his one permitted marker = **plain, slightly blunt
  phrasing** and dropped courtesy (*«No se ha presentado, señor Holmes.»*)
  — never eye-dialect, never *andaluz* spelling tricks; class shows in word
  choice and rhythm.
- **Officials (Lestrade, Thorne):** correct, a little stiff, professional.

## 12. IDIOM RE-ENGINEERING
Never literal: *"pulling my leg"* → **me está tomando el pelo** · *"raining
cats and dogs"* → **llovía a cántaros** · *"dead of night"* → **en plena
noche / a altas horas** · *"caught red-handed"* → **con las manos en la
masa** · *"a fortnight"* → **quince días / una quincena**. London colour
may be adapted to legible equivalents; keep it where a Spanish listener can
follow.

## 13. TYPOGRAPHY & ACCENTS
- **Opening ¿ and ¡ are mandatory** on every question/exclamation — see
  ES-03 (they are TTS-critical, not optional).
- Semicolons BANNED (ES-03 wins over literary habit).
- **Accents carry meaning — never drop them:** tú/tu, él/el, sí/si, sé/se,
  más/mas, té/te, dé/de, sólo(adv, optional but keep if used), aún/aun.
  A wrong accent can flip a word's sense for the TTS engine.
