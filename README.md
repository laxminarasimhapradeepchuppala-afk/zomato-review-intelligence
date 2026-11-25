# Zomato Restaurant Review Intelligence

This project analyzes supplied restaurant-review and restaurant-metadata CSV files. It follows a machine-learning submission structure and combines exploratory data analysis, statistical testing, rating-derived sentiment classification, and descriptive restaurant segmentation.

## Run in Google Colab
1. Upload `Zomato_Review_Intelligence.ipynb` through **File → Upload notebook**.
2. Run the first setup cell and upload the project ZIP when prompted.
3. Select **Runtime → Run all**.

## Run locally
Install the dependencies in `requirements.txt`, open the notebook in Jupyter or VS Code, and keep both CSV files in `data/` beside the notebook.

## Project files
- `Zomato_Review_Intelligence.ipynb` — analysis and model workflow.
- `data/restaurant_reviews.csv` — supplied review rows.
- `data/restaurant_metadata.csv` — supplied restaurant profiles.
- `Zomato_Review_Intelligence.pptx` — presentation summary.
- `DEMO_VIDEO_SCRIPT.md` — timed narration and screen cues for the required demo video.

## Scope and limitations
The review file contains 10,000 rows across 100 restaurant names; the metadata file contains 105 profiles. Sentiment labels are derived from ratings, so the text model predicts rating bands rather than independently verified human sentiment. Restaurant segments are descriptive and should be validated before business use. Findings describe this supplied sample only.

Contributor details and a repository URL may be added here before submission.
