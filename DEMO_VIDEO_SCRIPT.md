# Zomato Project Demo Video

**Target length:** 2–3 minutes  
**Format:** screen recording with spoken narration  
**What to show:** the notebook in Colab, then the project presentation  

## Recording setup

1. Open the notebook in Google Colab and choose **Runtime → Run all**. Wait for the charts, model comparison, and cluster summaries to finish.
2. Keep the notebook and presentation ready in separate browser tabs.
3. Start a screen recording, read the narration below, and show the screen cue for each section.
4. When you reach the model results, read the actual scores displayed in your run. Do not invent or reuse example numbers.

## Narration and screen cues

### 0:00–0:15 · Project question
**Show:** Notebook title and problem statement.

“Hello. This project analyzes Zomato restaurant reviews and restaurant details. I wanted to understand customer rating patterns, classify review text into rating-based sentiment groups, and explore how restaurants differ by cost, rating, and cuisine variety.”

### 0:15–0:35 · Data
**Show:** Data loading and the dataset shape/missing-value output. Avoid displaying reviewer names.

“The project uses two files: 10,000 review rows across 100 restaurants, and metadata for 105 restaurant profiles. I cleaned mixed rating values and matched restaurants by normalized name. Review counts are nearly balanced in this sample, so I do not treat them as a measure of real-world popularity.”

### 0:35–0:55 · Main findings
**Show:** Rating and cuisine charts, then listed cost chart.

“The numeric ratings average about 3.6 out of 5, and roughly 63 percent are four or five. The listed cost has a median of 700 rupees per person. North Indian and Chinese are the most common cuisine tags. These results describe only the supplied sample.”

### 0:55–1:25 · Sentiment model
**Show:** Sentiment-band chart, then model comparison and confusion matrix.

“I created three sentiment bands from the star ratings: negative, neutral, and positive. The notebook compares Logistic Regression, Linear SVC, and Multinomial Naive Bayes using TF–IDF text features. The results on screen show the model scores from this run. Because the labels come from ratings, these scores measure agreement with rating bands, not independently verified human sentiment.”

### 1:25–1:50 · Restaurant segments
**Show:** Silhouette scores, cluster summary, and segment scatter plot.

“I also used K-means to group restaurants by listed cost, average rating, review coverage, and cuisine and collection breadth. I compare candidate cluster counts with silhouette scores, then inspect the profiles. These segments are descriptive and are not restaurant quality rankings.”

### 1:50–2:10 · Limits and conclusion
**Show:** Limitations and conclusion sections.

“To improve the project, I would validate sentiment against human-labeled reviews, verify restaurant identifiers, test whether the clusters remain stable, and add more cities and time periods. Overall, this analysis is a starting point for understanding review patterns and restaurant profiles, not an automated decision system. Thank you.”

## Export from PowerPoint

If recording the presentation in PowerPoint, use **Record → From Beginning**, read the script while advancing the slides, then choose **File → Export → Create a Video** and select **Use Recorded Timings and Narrations**. Review the MP4 before submitting.
