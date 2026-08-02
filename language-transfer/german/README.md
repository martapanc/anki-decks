# Language Transfer — Complete German

Study material extracted from the transcript of the Language Transfer *Complete
German* course (50 tracks, the course's edited audio segment). Two kinds of files:

- **`lesson-summaries.md`** — a short topic summary for every one of the 50 tracks,
  grouped into 5 thematic parts.
- **`lt-de-*.csv`** — vocabulary/expressions for import into Anki, one CSV per thematic part.

## CSV format

Each row is `English,German` (English prompt first, German answer second). Files are
standard CSV: fields that contain a comma (e.g. multi-sense glosses) are double-quoted,
so they import cleanly. Vocabulary is de-duplicated within each file and a word is listed
under the track where it is first taught (capitalization is preserved, since it can be
meaningful in German — e.g. **Sie** "you [formal]" vs. **sie** "she/they").

## The 5 groups

| File | Tracks | Theme | Rows |
|------|--------|-------|------|
| `lt-de-01-07-cognates-sound-shifts-modals.csv` | 1–7 | Cognates, sound shifts & first modal verbs | 89 |
| `lt-de-08-16-modals-negation-word-order.csv` | 8–16 | Modal verbs, negation & verb-final word order | 158 |
| `lt-de-17-27-articles-gender-plurals.csv` | 17–27 | Articles, gender & noun plurals | 186 |
| `lt-de-28-40-separable-verbs-perfect-tense.csv` | 28–40 | Separable verbs & the perfect (past) tense | 206 |
| `lt-de-41-50-dative-case-pronouns.csv` | 41–50 | The dative case, pronouns & indirect objects | 102 |

Total: 741 entries. Track 1 is the course introduction and teaches no German.

## A note on the source

This transcript is a volunteer transcription of the course audio and contains
transcription errors and inconsistent track labeling. Track boundaries for the
summaries and CSVs above were reconstructed from context (and cross-checked
against the transcript's own page markers where present), so a small number of
track splits are inferred rather than taken from an explicit label.
