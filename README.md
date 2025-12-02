# Real Time Fake News Prediction

## Team Members

- **Ritik Agrawal** - Email: ritikagarwal@iisc.ac.in
- **Sanjana R** - Email: sanjana2@iisc.ac.in
- **Himanshu Sharma** - Email: himanshu5@iisc.ac.in
- **Mayank Teckchandani** - Email: tmayank@iisc.ac.in

## Problem Statement

In today's digital age, we're drowning in information. But how much of it is true?

- Social media spreads news at lightning speed.
- Misinformation spreads faster than truth.
- People can’t deal with thousands of articles being generated every day.

**Can machines help us detect fake news automatically?**

The goal is to build a system that:
- Automatically provides a probability for a news story to be fake or real using distributed machine learning.
- Achieves a target confidence score of 80%.
- Decreases the number of humans required by over 10 times to make the pipeline accurate and scalable enough to handle the massive data being generated.

## Dataset Description

To understand what makes fake news different from real news, we:

- Loaded a dataset of thousands of news articles (both fake and real).
- Each article included a title, text content, and a label (Fake, Real).

### First Impressions:
- The dataset contained a mix of political, social, and general news.
- Articles varied greatly in length and writing style.
- Both titles and full article text were available for analysis.

### Key Statistics:
- The dataset contains **More than 80,000 data points**.

## Approach and Methods

We followed a systematic approach to build and refine our fake news detection system:

1. **Baseline Machine Learning Model:**
   - Used Logistic Regression with TF-IDF (Term Frequency-Inverse Document Frequency) features.

2. **Ensemble Method:**
   - Implemented XGBoost to improve prediction accuracy by combining multiple weak learners.

3. **Deep Learning Model:**
   - Developed a Bi-LSTM (Bidirectional Long Short-Term Memory) model to:
     - Understand contextual meaning.
     - Capture long-range dependencies for better differentiation between fake and real news patterns.

## Results Summary

- Achieved a target confidence score of approx. 95%.
- Successfully reduced the need for human intervention by over 10 times.
- The system is scalable and capable of handling massive amounts of data being generated daily.

## Resources
- [Project Repository](https://github.com/dlquad/iisc-ds-project)
- [Presentation Slides](docs/Real-Time_Fake-News_Prediction_CourseProject_Slides.pptx)
- [Final Report](docs/Real-Time_Fake-News_Prediction_CourseProject_Report.docx)
- [Data Science Canvas](docs/Real-Time_Fake-News_Prediction_CourseProject_Canvas.pptx)
---


*Last Updated: December 1, 2025*

