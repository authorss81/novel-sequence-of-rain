# Review: Volume 02, Batch 0003 (Chapters 71–82)

Reviewed after the writer's commit. Twelve chapters, the batch outline, six state files, one next-phase prompt. Working tree clean; no controller file touched. **The batch was repaired, not restarted: no chapter was rewritten, no scene removed, no binding or panel changed, and the planned plot is identical to the batch the writer delivered.**

## Verified sound

- **All twelve chapters are finished prose**, 2,528–3,164 words, complete scenes with a goal, a resistance from a named person, a change and an ending. No truncation, no mid-sentence cutoff, no padded scene.
- **One binding and one System panel in the batch, Chapter 81 only, and both are the sixth ward's.** Complies with the one-panel rule and with *no panel may be Marek's*.
- **Guardrails held.** Dellow's schedule still unsent and known to nobody but him (Ch 80); the holder and the substrate are never touched in the tower and the spare plate stays boxed and unfitted (Ch 75); the column head still reads CLAIM — DISPLACED TURNS and is correctly *not* changed, that being reserved for Ch 96; no Gregorian month name introduced; *partnership* unused; the three uncompellable books enumerated in Ch 77; Anja dead and unmentioned; Ione Sere and Ottine Vask off the page; no death, no hours-to-arrival.
- **Act III's turn lands** — Ch 82: the Exchange withdraws the reach line in public and prints the ninth ward's own figure with the eleven-shilling receipt under it.
- **Exactly one next-phase prompt** was created, `workspace/volume-02/batch-0004/PROMPT.md`.

## Defects, and what was done about each

| # | Defect | Repair |
| --- | --- | --- |
| 1 | **Ch 74 dated its opening scene to the Monday the twentieth.** The twentieth is a Sunday; the chapter's own Wednesday the twenty-third forced Monday to be the twenty-first. | Prose corrected to *the Monday morning of the twenty-first*. The rest of the week was already right and did not move. |
| 2 | **Ch 80's closing scene ran backwards against Ch 82's clock.** At a quarter past eight Petrie predicts forty tons by about ten and the masons in at seven; the tide turns at four minutes past seven in Ch 82 and the masons are released at seven. | **Repaired in the hour, not in the speech.** The scene now runs at about ten past six, when a shed foreman reads a level book and when the man who left two sheets on a drum at eleven the night before is on the flat again. The bell line became *went over a chandler yesterday afternoon*, which is when it went. **Rewriting Petrie into the past tense was rejected: it would have told the reader the tide had failed a chapter before Ch 82, which is the batch's cliff.** |
| 3 | **The ninth ward's glass had three different figures** — the middle of the Bellweather month in Ch 75 and Ch 81, the middle of the autumn before last in Ch 58 — and `outline/volume-02.md` and the Batch 0004 prompt were both about to hand a writer a closing image of *nine months*, which no chapter supports. | **One figure: the middle of the Bellweather month**, in Ch 58 (three places), the outline, the prompt, `state/current.md` and `state/continuity.md`. **The autumn before last now belongs to the bubbled temporary in the frame** and to nothing else. *No chapter may print a number of months for the dark.* |
| 4 | **`state/chapter-summaries.md` diverged from the prose in five places** — Ch 74's day, Ch 75's and Ch 81's glass, Ch 76's post day, Ch 82's masons — because the summaries were drafted from the plan in the same pass as the prose. | All five corrected, and Ch 80's shed scene given the corrected hour. |
| 5 | **`state/chapter-summaries.md` was structurally out of order**: the Batch 0003 entries had been prepended above the Volume 01 heading in a bulleted format nothing else in the file uses. | Rebuilt. Batch 0003 is now the last section, in batch order, in the established `### Chapter 00NN` format, with the file's descriptive header restored. |
| 6 | **Authorial meta-language in the narration**: *it is the whole of the chapter's problem in eleven words* (Ch 74), *it is the reason the chapter is called what it is called* and *the fourth this volume* (Ch 81). | Clauses cut, sentences kept. **A fourth instance was found and cut in Ch 66, which was the last of them in Volume 02.** Volume 01 has the same tic in Ch 41, 43 and 44 and was **not** touched — this repairs Volume 02, it does not retrofit Volume 01. |
| 7 | **Bolded asides restate the moral of the beat just dramatised** — 5 to 15 a chapter. | **A light, targeted pass only.** Four asides cut or shortened, all of them naming a theme or repeating a beat two paragraphs later (Ch 74, Ch 75 ×2, Ch 79). 104 words out, none in. **Volume 02's aside density is a deliberate three-batch manner, not padding, and was deliberately not flattened**; the Batch 0004 prompt now carries a calibration number instead. |

## Also fixed, not in the reviewer's list

- **Ch 82 gave one distance twice** — three feet in two places, six inches in the third. Now three feet everywhere, with `state/current.md` and `state/open-threads.md` corrected, the latter having carried both figures in one line.
- **Stale word counts in two state files.** Batch 0001, Batch 0002 and the Volume 01 totals were measured before later repair passes added words. Re-measured: Volume 01 172,671; Batch 0001 36,887; **Batch 0002 44,697, not 41,725**; Batch 0003 32,827; Volume 02 114,410.
- **The Batch 0004 prompt carried three of these errors forward** and was corrected in place, plus a new section carrying all nine findings forward.

## Notes, not defects

- The batch plan was written in the same commit as the prose, so there was no independent plan to check the chapters against. **Finding 4's likeliest origin is that the outline, the summaries and the prompt all came from the same draft as the chapters.** The Batch 0004 prompt now instructs the writer to write the plan first and the summaries afterwards, from the finished chapters.
- **Length is trending down**: 3,686, 3,477, 2,736 words a chapter, against Volume 01's 3,597. Nothing is padded and every scene completes. Batch 0004 has a hearing, a ledger, a document becoming admissible and a tower lighting up in it, and the prompt is told not to close the volume a quarter under Volume 01's density.
- **No review artefact existed for any batch** — `reviews/` held only its README. This file is the first, and the findings are also carried in `state/current.md`, `state/continuity.md`, `state/batch-summaries.md` and the Batch 0004 prompt, because a review that lives only in a phase log is a review the next writer never sees.
