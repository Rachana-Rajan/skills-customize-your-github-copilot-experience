# 📘 Assignment: Python Text Processing

## 🎯 Objective

Practice string manipulation, file I/O, and text processing in Python. Students will read input from a text file, transform data, and write results to a new file.

## 📝 Tasks

### 🛠️ Read and analyze text file data

#### Description
Load a text file, clean lines, and summarize content statistics.

#### Requirements
Completed program should:

- Open `input.txt` in read mode
- Normalize text by stripping whitespace and removing special characters
- Count total words, unique words, and line count
- Print text summary to console

### 🛠️ Implement search and replace operations

#### Description
Search for a target word and replace with new text across the file content.

#### Requirements
Completed program should:

- Accept `search_word` and `replacement` variables
- Replace all case-insensitive occurrences in the text
- Print number of replacements made
- Save updated text to `output.txt`

### 🛠️ Create a word frequency report

#### Description
Generate a frequency report for words in the cleaned text and save it as CSV.

#### Requirements
Completed program should:

- Create a dict of word counts from cleaned text
- Sort by frequency descending
- Write report to `word_frequency.csv` with `word,count` columns

## 💡 Optional extensions

- Support command-line arguments for input/output filenames
- Add stopword filtering (e.g., `a`, `the`, `and`)
- Implement simple summary metrics like average sentence length
