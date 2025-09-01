# Student Plagiarism Checker

This Python project is designed to detect plagiarism among students' text files by comparing the similarity of their notes using **TF-IDF vectorization** and **cosine similarity**.

---

## Features

- Automatically scans all `.txt` files in the current directory.
- Vectorizes text using **TF-IDF (Term Frequency-Inverse Document Frequency)**.
- Computes **cosine similarity** between all student notes.
- Identifies potential plagiarism and outputs similarity scores between student files.
- Avoids duplicate comparisons by sorting student pairs alphabetically.

---

## How It Works

1. **Load Student Notes**: All text files in the directory are read and stored.
2. **Vectorize Text**: Each student's notes are converted into numerical vectors using TF-IDF.
3. **Compute Similarity**: Cosine similarity is calculated between each pair of student notes.
4. **Store Results**: The similarity scores along with student file names are stored in a set to prevent duplicates.
5. **Display Results**: Prints all similarity scores, highlighting potential plagiarism.

---
