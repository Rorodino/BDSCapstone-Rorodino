# Wine Dataset Capstone Project

This repository contains the deliverables for the wine chemical analysis capstone project inspired by *Data Science & AI for Bio/medical*. The study investigates how chemical properties differentiate three wine cultivars and demonstrates a full analytics workflow in Python.

## Repository Contents
- `Wine_Analysis.ipynb` — Google Colab-compatible notebook with the complete data pipeline.
- `WRITEUP.md` — Narrative report (3–5 pages when converted to PDF) that excludes code blocks but references key figures.
- `data/` — Generated at runtime by the notebook (no raw data needed because the dataset is loaded from `scikit-learn`).

## Quick Start
1. Open [Google Colab](https://colab.research.google.com/) and upload `Wine_Analysis.ipynb`.
2. Ensure the runtime uses Python 3 and a GPU is **not** required.
3. Run the notebook cells sequentially. All data are loaded via `scikit-learn`, so no additional downloads are needed.
4. Export plots as PNG files if you want to insert them into the written report or presentation.

## Video Presentation
A short presentation (< 5 minutes) that summarizes the project is available here:

- [Capstone Presentation Video](https://example.com/your-video-link)

Make sure the hosting service permissions are set to **"anyone with the link"** so instructors can access the video.

## How to Generate the PDF Write-up
1. Open `WRITEUP.md` in a Markdown editor or viewer (e.g., VS Code, Typora, Dillinger, or `pandoc`).
2. Export the document to PDF. The structure is formatted to produce between three and five pages when standard margins and a 11–12 pt font are used.
3. Insert relevant figures exported from the notebook into the designated placeholders before conversion.

## References
- UCI Machine Learning Repository — Wine Data Set.
- Forina, M., et al. (1990). *Chemometrics and Intelligent Laboratory Systems*, 8(1), 49–60.
- Pedregosa, F., et al. (2011). *Journal of Machine Learning Research*, 12, 2825–2830.

---

**Author:** Your Name Here
