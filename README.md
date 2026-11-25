# 3i4k utterance intent — 30,000-sentence sample

Data for the Introduction to AI (2026 Fall) term project, track D (text classification).

- **Source:** FCI corpus of 3i4k (`data/fci.txt`), https://github.com/warnikchow/3i4k
  Cho, W. I., Lee, H. S., Yoon, J. W., Kim, S. M., & Kim, N. S. (2018). *Speech Intention Understanding in a Head-final Language: A Disambiguation Utilizing Intonation-dependency.* arXiv:1811.04231.
- **License:** CC BY-SA 4.0 (https://creativecommons.org/licenses/by-sa/4.0/). This derived file is shared under the same license.
- **Changes from the original:**
  1. Removed 215 sentences that appear with different labels (536 rows).
  2. Removed 3,656 exact duplicate rows (57,063 unique sentences left).
  3. Sampled 30,000 sentences at random (seed 2026) and shuffled the row order.
  4. Renamed labels 0–6 to `fragment`, `statement`, `question`, `command`, `rhetorical_question`, `rhetorical_command`, `intonation_dependent`.
- **Columns:** `text` (one Korean utterance, no punctuation), `label`.
