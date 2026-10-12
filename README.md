# Machine Learning Course Notes

Personal repository for my practice work in the Machine Learning course taught by PGS.TS Nguyen Tan Tran Minh Khang at UIT: exercises, notebooks and small experiments, organized by session.

Course slides and third-party datasets are not redistributed here. Sources are cited where they are used.

## Contents

Exercises are added session by session as they are completed.

| Session | Topic | Status |
|---------|-------|--------|
| 02 | Linear vs. Polynomial Regression (salary prediction) | [`Buoi2.ipynb`](./session-02-linear-regression/Buoi2.ipynb) |

## Study Notes

Written notes for each lecture, kept in [`notes/`](./notes). Each file covers one lecture, in Vietnamese, and follows the slide order.

| # | Topic | File |
|---|-------|------|
| 01 | Introduction to Machine Learning | [`01-introduction-to-machine-learning.docx`](./notes/01-introduction-to-machine-learning.docx) |
| 02 | Simple Linear Regression | [`02-simple-linear-regression.docx`](./notes/02-simple-linear-regression.docx) |
| 03 | Multiple Linear Regression | [`03-multiple-linear-regression.docx`](./notes/03-multiple-linear-regression.docx) |
| 04 | Polynomial Regression | [`04-polynomial-regression.docx`](./notes/04-polynomial-regression.docx) |

## Running the Notebooks

Each session folder contains its own notebook. Session 02 reads `Position_Salaries.csv`, which is provided with the course and not included here, so place it in the same folder before running. To run locally:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
jupyter notebook
```

## Notes on Sources

- Lecture material belongs to the course instructors and is not included.
- The notes in `notes/` are my own study summaries written from the lecture slides. They are not the slides themselves.
- Datasets are either provided by the course or cited with their original source.
- Code is written by me unless a file header says otherwise.

## Author

**Nguyen Thanh Thien Nhan (bersious)**, Artificial Intelligence (Trí tuệ nhân tạo), UIT
