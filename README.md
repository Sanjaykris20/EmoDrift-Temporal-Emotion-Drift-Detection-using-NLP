📘 EmoDrift — Temporal Emotion Drift Detection using NLP

EmoDrift is an NLP-based project that goes beyond traditional sentiment analysis by detecting temporal emotional trends and mood drift in text data. Rather than just classifying text as positive/negative/neutral, EmoDrift analyzes how sentiment changes over time and identifies points where collective mood significantly shifts.

This approach has real-world uses in areas such as social media trend tracking, customer feedback evolution, employee sentiment monitoring, mental health analysis, and more.

🔍 Project Motivation

Most sentiment analysis systems evaluate text independently — assigning a positive, negative, or neutral label to each piece of text. However, emotions evolve over time, and understanding those dynamics offers deeper insight into behavioral trends.

EmoDrift fills this gap by:

✅ Tracking sentiment changes through time
✅ Aggregating emotional scores over intervals
✅ Identifying emotion drift points
✅ Providing visual insights into overall mood evolution

💡 Key Features

Temporal sentiment aggregation

Mood drift detection and trend analysis

Visual graphs of emotional changes

Designed for short and long text inputs

📊 How It Works — NLP Pipeline

Load and Inspect Dataset
Time-stamped text entries for trend analysis.

Text Preprocessing

Lowercase conversion

Removal of punctuation and noise

Tokenization

Stopwords removal

(Optional) Lemmatization

Sentiment Scoring
Calculate emotion scores per entry (e.g., polarity, subjectivity).

Time-based Aggregation
Group sentiment by time intervals (daily, weekly, etc.).

Mood Drift Detection
Analyze aggregated scores to find notable shifts.

Visualization
Plot sentiment lines and highlight drift boundaries.

Interpretation & Insights

🛠️ Tools & Technologies
Feature	Technology
NLP	Python, NLTK/TextBlob/VADER
Data Handling	Pandas, NumPy
Visualization	Matplotlib / Seaborn
Analysis	Time-series sentiment aggregation

You can extend this with transformer models or deep learning for more advanced sentiment features. 
GitHub

📁 Repository Structure
📦 EmoDrift-Temporal-Emotion-Drift-Detection-using-NLP
 ┣ 📜 Mood_drift_detector_nlp_short.ipynb    # Core notebook
 ┣ 📜 README.md                              # This file
 ┗ 📜 requirements.txt                        # Python dependencies

🚀 How to Get Started

Clone the repo

git clone https://github.com/Sanjaykris20/EmoDrift-Temporal-Emotion-Drift-Detection-using-NLP.git


Install dependencies

pip install -r requirements.txt


Run the notebook

jupyter notebook Mood_drift_detector_nlp_short.ipynb


Explore the output visualizations and sentiment drift insights.

🧪 Example Use Cases

📈 Social Media Trend Analysis – Detect changes in public mood

🗣️ Customer Feedback Evolution – See how customers’ sentiment changes over time

🧠 Mental Health Monitoring – Track emotional shifts across diary entries

📊 Business Intelligence – Report on emotional trends for strategic decisions

📌 Notes & Tips

For more accuracy on large datasets, consider upgrading sentiment scoring using transformer-based models.

Combine this with topic modeling to see what topics fuel emotional shifts.
