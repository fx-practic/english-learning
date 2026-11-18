# English Learning

Personal English vocabulary collection, starting with **UHI ESOL travel vocabulary**.

## Vocabulary

- **30 English words and expressions** from the ESOL travel homework (18 November 2026).
- **11 positive**, **10 negative** and **9 neutral** descriptions/actions.
- Each entry includes **multiple context-aware Russian translations**, a part of speech, an English example, its Russian translation and a usage note.
- Main dataset: [data/vocabulary.json](data/vocabulary.json).

## Intended use

The JSON file is the source of truth for a future vocabulary practice application (flashcards, English–Russian translation exercises, spaced repetition, quizzes). **No application has been implemented yet.** New words can be appended as additional records rather than replacing existing vocabulary.

## Data conventions

- Use a unique lowercase hyphenated `id` and the original expression in `english`.
- `category` is `positive`, `negative`, or `neutral`. These are approximate and may change with context.
- `translations_ru` lists natural Russian equivalents relevant to the travel topic; alternatives are not necessarily interchangeable in every sentence.
- `example_en` / `example_ru` are paired sentence examples.
- `usage_note_ru` explains nuance, collocations, or other meanings where useful.
- Keep this UTF-8 JSON valid and preserve earlier words when expanding the collection.
