# Language Transfer — Complete Spanish

Study material extracted from the transcript of the Language Transfer *Complete Spanish*
course (90 tracks). Two kinds of files:

- **`lesson-summaries.md`** — a short topic summary for every one of the 90 tracks,
  grouped into 9 thematic parts.
- **`lt-*.csv`** — vocabulary/expressions for import into Anki, one CSV per thematic part.

## CSV format

Each row is `English,Spanish` (English prompt first, Spanish answer second). Files are
standard CSV: fields that contain a comma (e.g. multi-sense glosses like
`"he/she/it is, you (formal) are"`) are double-quoted, so they import cleanly.

Vocabulary is de-duplicated within each file and a word is listed under the track where
it is first taught. The course is a spiral grammar course, so the groups are grammatical
themes rather than topics like "food" or "colours".

## The 9 groups

| File | Tracks | Theme | Rows |
|------|--------|-------|------|
| `lt-01-09-cognates-and-first-sentences.csv` | 1–9 | Cognates & first sentences | 163 |
| `lt-10-18-present-tense-and-stem-changes.csv` | 10–18 | The present tense & stem-changing verbs | 161 |
| `lt-19-24-perfect-past-and-pronouns.csv` | 19–24 | The perfect past (haber) & the pronoun system | 62 |
| `lt-25-35-reflexives-numbers-time-ser-estar.csv` | 25–35 | Reflexives, numbers, time & ser vs estar | 116 |
| `lt-36-45-future-conditional-gustar-prepositions.csv` | 36–45 | Future & conditional; gustar-type verbs; prepositions | 105 |
| `lt-46-55-imperfect-pluperfect-por-para.csv` | 46–55 | Imperfect & pluperfect pasts; por/para; participles | 109 |
| `lt-56-68-preterite-relatives-possession.csv` | 56–68 | The preterite (simple past); relatives & possession | 128 |
| `lt-69-83-subjunctive-mood-tense.csv` | 69–83 | The subjunctive (mood tense) | 119 |
| `lt-84-90-irregular-verbs-and-dialects.csv` | 84–90 | Irregular verbs & dialect variation | 71 |

Total: ~1,034 entries. Track 1 is the course introduction and teaches no Spanish.