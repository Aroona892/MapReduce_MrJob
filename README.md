# 🗃️ MapReduce with mrjob (Word & Alphabet Count)

This project demonstrates **MapReduce programming** using the `mrjob` Python library. It includes two jobs: one for counting characters, words, and lines; and another for counting how many words start with each alphabet letter.

---

## 🧠 Jobs Overview

### 🔢 MRWordFrequencyCount
- **Mapper**: Emits counts of characters, words, and lines per line.
- **Reducer**: Sums the totals for each key.

### 🔡 WordsByAlphabet
- **Mapper**: Extracts first letter of each word and emits `(letter, 1)`
- **Reducer**: Aggregates counts for each letter (case-insensitive)

---

## 🛠 Tools Used

- Python
- `mrjob` (MapReduce job runner)

---

## 🚀 How to Run

1. Install dependencies:
```bash
pip install mrjob
