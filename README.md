# Networks of Denunciation — Two Channels 參劾之網

An interactive visualization of who denounced whom in the bureaucracy of Qing China under
the Yongzheng Emperor (1723–1735), across the state's two reporting circuits:

- **題本 · the routine channel** — 3,373 reporter→reported-on ties extracted from 24,545
  entries of the Board of Personnel routine memorials (吏科題本): governors and
  governors-general naming county magistrates in open procedure.
- **奏摺 · the secret channel** — 1,836 denunciation (彈劾) and recommendation (保舉) ties
  from the secret palace-memorial corpus (硃批奏摺): the provincial elite denouncing and
  recommending one another directly to the emperor.

**Live page:** `https://<username>.github.io/<repo>/denunciation/` *(edit after enabling Pages)*

## What's in the explorer

An interactive network (filter by channel, reign year, and action type; click a hub to
isolate its ego network), a who-reports-on-whom office matrix, the two channels' contrasting
tempos (the routine channel keeps the statutory 大計 triennial clock; the secret channel
surges with political weather), the chief accusers in each channel, and the tail of the
distribution — novel targets, pile-on targets, and reciprocal feuds.

## Data protection

**This page is a visualization, not a data release.** The underlying datasets are unpublished
and part of an ongoing research project.

- Only 70 officials are named — the most active reporters/senders in each channel and a small
  set of independently verified or already-contested senior figures, all persons of the public
  historical record. Every other official appears as an anonymous rank (「知縣」, "a county
  magistrate").
- The embedded data contain no memorial text, no day-level dates, no place names attached to
  anonymized individuals, no memorial IDs, and no downloadable edge table. Ties readable with
  both endpoints named are 118 of 5,209 (2.3%) — essentially the famous cases of the standard
  histories.
- Please do not attempt to reconstruct or redistribute the underlying data. For data or
  collaboration inquiries, contact the author.

## Methods, briefly

Routine-channel ties are extracted from OCR-corrected and proofread 吏科題本 text by
surname-anchored extraction (~5–10% residual noise remains); action types are approximate,
assigned by matching ties to same-day entries (93.7% match) and keyword-classifying subject
lines — about a third of routine ties are clearly disciplinary (參劾-type). Secret-channel
ties carry the research dataset's own 彈劾/保舉 coding. Sender offices follow the Academia
Sinica officeholder reference. The network layout is precomputed and deterministic; visual
proximity between hubs is an artifact of the layout, not a measured quantity. Fuller method
notes and caveats are in the page footer.

## Technical notes

The page is a single self-contained HTML file — no external libraries, no network requests,
no tracking. It runs entirely in the browser; open it locally or serve it from any static
host (e.g. GitHub Pages).

## Status & attribution

Part of an ongoing joint research project on secret reporting and elite control in Qing
China; a working paper is in preparation. Visualization by Cheng Cheng (NYU).
Comments and corrections welcome.
