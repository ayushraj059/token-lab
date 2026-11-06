# Token Lab: Tokenization and Context Window Management

A 45-minute, self-paced interactive lesson on how LLMs tokenize text and how to manage the context window in real AI applications.

**Run it:** download or clone this repo and open `index.html` in any modern browser. No install, no API key, works offline.
Live version (if GitHub Pages is on): see the link in the repo sidebar.

## Lesson plan (45 min)
| Part | Minutes | What the learner does |
|---|---|---|
| Intro | 4 | Reads objectives and why tokens matter |
| 1. BPE by hand | 9 | Steps through merges, predicts each winner |
| 2. Token playground | 8 | Compares English, Tamil, code, digits |
| 3. Context window | 10 | Watches a chatbot forget an allergy, tries 3 fixes |
| 4. Budget challenge | 8 | Splits an 8,000-token window under constraints |
| 5. Quiz and code | 6 | 5 questions, real Python trimming function |

## Accuracy note
The playground tokenizer is a toy BPE trained in the browser on a small English paragraph. Real tokenizers (e.g. tiktoken) have 100k+ merges, so counts differ; the behaviour is the same. Prices in Part 4 are illustrative.

## Files
`index.html` (the whole lesson, single file) and this README.
