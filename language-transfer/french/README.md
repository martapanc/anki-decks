# Language Transfer — Introduction to French

Study material extracted from the transcript of the Language Transfer *Introduction to
French* course (40 tracks). Two kinds of files:

- **`lesson-summaries.md`** — a short topic summary for every one of the 40 tracks,
  grouped into 5 thematic parts.
- **`lt-fr-*.csv`** — vocabulary/expressions for import into Anki, one CSV per thematic part.

## CSV format

Each row is `English,French` (English prompt first, French answer second). Files are
standard CSV: fields that contain a comma (e.g. multi-sense glosses) are double-quoted,
so they import cleanly. Vocabulary is de-duplicated within each file and a word is listed
under the track where it is first taught. As a spiral course, the groups are grammatical
themes rather than topics like "food" or "colours".

## The 5 groups

| File | Tracks | Theme | Rows |
|------|--------|-------|------|
| `lt-fr-01-08-cognates-first-sentences-gender.csv` | 1–8 | Cognates, first verbs & gender | 84 |
| `lt-fr-09-16-pronouns-numbers-articles-liaison.csv` | 9–16 | Pronouns, numbers, articles & liaison | 67 |
| `lt-fr-17-24-nouns-negation-present-etre.csv` | 17–24 | Nouns, negation, the present & être | 58 |
| `lt-fr-25-32-lost-s-reflexives-question-words.csv` | 25–32 | The "lost S", reflexives & question words | 67 |
| `lt-fr-33-40-adjectives-re-verbs-future-past.csv` | 33–40 | Adjectives, RE verbs, near future & perfect past | 79 |

Total: ~355 entries. Track 1 also opens the course (there is no separate intro track).