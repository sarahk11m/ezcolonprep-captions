# Caption Review Log

Tracks that have been manually verified word-by-word against the approved scripts in
`docs/translations/approved/` in the main repo. Each row records what was checked, any
errors found, and the commit that fixed them.

---

## balex/en — 11 files ✅ verified 2026-06-30

| File | Key | Errors found |
|------|-----|-------------|
| weekbefore.vtt | wb-rec-main | none |
| glp1.vtt | wb-glp1 | none |
| iron.vtt | wb-iron | none |
| dayb4.vtt | db-rec-1 | none |
| tips_night.vtt | nb-rec-vomit | none |
| daybefore_clenpiq.vtt | bp-4 | none |
| daybefore_miralax.vtt | bp-2 | none |
| daybefore_peg.vtt | bp-pegone | none |
| daybefore_plenvu.vtt | bp-plenvu | none |
| daybefore_suprep.vtt | bp-1 | none |
| daybefore_sutab.vtt | bp-sutab | none |

> Note: balex/en has 11 files (original batch). Missing vs 18-file set: med-hold-main, db-opt-diabetes, nb-rec-1, nb-opt-1, do-rec-1, do-opt-bp, do-opt-seizure — these videos have no captions yet for balex/en.

---

## balex/ko — 7 files ✅ verified 2026-06-30

| File | Key | Errors found | Fix commit |
|------|-----|-------------|------------|
| night_vomiting.vtt | nb-rec-vomit | none | — |
| daybefore_clenpiq.vtt | bp-4 | none | — |
| daybefore_miralax.vtt | bp-2 | none | — |
| daybefore_peg.vtt | bp-pegone | "페그" → "PEG" ×2 (ASR phonetically transcribed English abbreviation) | e815ee7 |
| daybefore_plenvu.vtt | bp-plenvu | none | — |
| daybefore_suprep.vtt | bp-1 | none | — |
| daybefore_sutab.vtt | bp-sutab | none | — |

---

## gjoy/en — 18 files ✅ verified 2026-06-30

| File | Key | Errors found | Fix commit |
|------|-----|-------------|------------|
| wb-rec-main.vtt | wb-rec-main | none | — |
| wb-glp1.vtt | wb-glp1 | none | — |
| wb-iron.vtt | wb-iron | none | — |
| med-hold-main.vtt | med-hold-main | none | — |
| db-rec-1.vtt | db-rec-1 | none | — |
| db-opt-diabetes.vtt | db-opt-diabetes | none | — |
| nb-rec-1.vtt | nb-rec-1 | none | — |
| nb-rec-vomit.vtt | nb-rec-vomit | none | — |
| nb-opt-1.vtt | nb-opt-1 | none | — |
| do-rec-1.vtt | do-rec-1 | none | — |
| do-opt-bp.vtt | do-opt-bp | none | — |
| do-opt-seizure.vtt | do-opt-seizure | none | — |
| bp-4.vtt | bp-4 | none | — |
| bp-2.vtt | bp-2 | none | — |
| bp-pegone.vtt | bp-pegone | "Your prep is the large container" missing "PEG" (ASR word drop) | 94daf1e |
| bp-plenvu.vtt | bp-plenvu | none | — |
| bp-1.vtt | bp-1 | none | — |
| bp-sutab.vtt | bp-sutab | none | — |

---

## pkim/ko — 18 files ✅ verified 2026-06-30

| File | Key | Errors found | Fix commit |
|------|-----|-------------|------------|
| wb-rec-main.vtt | wb-rec-main | none | — |
| wb-glp1.vtt | wb-glp1 | none | — |
| wb-iron.vtt | wb-iron | none | — |
| med-hold-main.vtt | med-hold-main | none | — |
| db-rec-1.vtt | db-rec-1 | "알콜" → "알코올" (ASR used informal spelling; approved script has official form) | e815ee7 |
| db-opt-diabetes.vtt | db-opt-diabetes | none | — |
| nb-rec-1.vtt | nb-rec-1 | none | — |
| nb-rec-vomit.vtt | nb-rec-vomit | none | — |
| nb-opt-1.vtt | nb-opt-1 | none | — |
| do-rec-1.vtt | do-rec-1 | none | — |
| do-opt-bp.vtt | do-opt-bp | none | — |
| do-opt-seizure.vtt | do-opt-seizure | none | — |
| bp-4.vtt | bp-4 | "ClenPIQ을" → "ClenPIQ를" (wrong particle: Q=큐 ends in vowel → 를) | e815ee7 |
| bp-2.vtt | bp-2 | none | — |
| bp-pegone.vtt | bp-pegone | none | — |
| bp-plenvu.vtt | bp-plenvu | none | — |
| bp-1.vtt | bp-1 | none | — |
| bp-sutab.vtt | bp-sutab | none | — |

---

## tabernathy/en — 18 files ✅ verified 2026-06-30

| File | Key | Errors found | Fix commit |
|------|-----|-------------|------------|
| wb-rec-main.vtt | wb-rec-main | none | — |
| wb-glp1.vtt | wb-glp1 | "phentermine" split mid-word by Whisper (str.replace collision) | 6487ccf |
| wb-iron.vtt | wb-iron | "Iron" capitalization | 6487ccf |
| med-hold-main.vtt | med-hold-main | none | — |
| db-rec-1.vtt | db-rec-1 | none | — |
| db-opt-diabetes.vtt | db-opt-diabetes | none | — |
| nb-rec-1.vtt | nb-rec-1 | none | — |
| nb-rec-vomit.vtt | nb-rec-vomit | none | — |
| nb-opt-1.vtt | nb-opt-1 | "dose as directed" word order | 6487ccf |
| do-rec-1.vtt | do-rec-1 | none | — |
| do-opt-bp.vtt | do-opt-bp | none | — |
| do-opt-seizure.vtt | do-opt-seizure | none | — |
| bp-4.vtt | bp-4 | ClenPIQ ×4 casing | 6487ccf |
| bp-2.vtt | bp-2 | MiraLAX ×3, Dulcolax word-split, "follow along", "232 ounce" → "two 32-ounce", Dulcolax tablets casing | 6487ccf + 0f6cd38 |
| bp-pegone.vtt | bp-pegone | "Your prep is" → "Your PEG prep is"; "crystal light" → "Crystal Light" ×2; "gulp at all at once" → "gulp it all at once" | 0f6cd38 |
| bp-plenvu.vtt | bp-plenvu | none | — |
| bp-1.vtt | bp-1 | SUPREP casing, "double-to" artifact | 6487ccf |
| bp-sutab.vtt | bp-sutab | SuTab ×2 casing | 6487ccf |

---

## Not yet verified

| Doctor | Lang | File count | Notes |
|--------|------|------------|-------|
| balex | en | 7 missing | med-hold-main, db-opt-diabetes, nb-rec-1, nb-opt-1, do-rec-1, do-opt-bp, do-opt-seizure not yet captioned |
| gjoy | ko | — | not yet captioned |
| gjoy | es | — | not yet captioned |
| gjoy | zh | — | not yet captioned |
| kim | en | TBD | not yet reviewed |
| pkim | en | TBD | not yet reviewed |
| tabernathy | ko | — | not yet captioned |
| tabernathy | es | — | not yet captioned |
| tabernathy | zh | — | not yet captioned |
