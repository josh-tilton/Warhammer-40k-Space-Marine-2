# Warhammer 40k: Space Marine 2 Player Feedback Analysis

## Project Overview

This project analyzes **Steam reviews** for the game _Warhammer 40k: Space Marine 2_, with the goal of extracting key insights from player feedback. By applying **Natural Language Processing (NLP)** techniques, the project identifies common themes in both **positive (Recommended)** and **negative (Not Recommended)** reviews, helping to understand critical gameplay elements and technical issues.

## Key Objectives

- **Identify common feedback** for both positive and negative reviews using n-grams (word combinations).
- **Apply TF-IDF** (Term Frequency-Inverse Document Frequency) to highlight important phrases and key topics.
- **Visualize frequent n-grams** to reveal player sentiments about gameplay, performance, and technical issues.

## Dataset

The dataset contains player reviews from _Steam_, categorized into:

- **Recommended**: Positive feedback
- **Not Recommended**: Negative feedback

Each review has been pre-processed into tokenized words and includes metadata such as review length and playtime.

## Methodology

1. **Data Preprocessing**: Tokenized reviews are converted into meaningful phrases (n-grams) to extract key topics.
2. **TF-IDF Analysis**: Extracts the most relevant bi-grams, tri-grams, and higher-order n-grams for each review category.
3. **Visualization**: Generates visualizations for the top n-grams based on their TF-IDF scores, providing insights into the most frequently discussed topics.
4. **Technical Issues and Praise**: Distills key technical complaints (e.g., crashes, performance) and gameplay features (e.g., fun, thematic immersion) from the reviews.

## Key Findings

- **Positive Reviews**: Highlight gameplay enjoyment, thematic immersion, and the strong Warhammer 40k universe experience.
- **Negative Reviews**: Focus on technical issues such as crashing, loading screens, and lack of ultrawide support.
