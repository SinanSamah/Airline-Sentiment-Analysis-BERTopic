# NLP Analysis of Airline Customer Feedback using BERTopic ✈️

This project performs an end-to-end analysis of the "Twitter Airline Sentiment" dataset. It uses the advanced BERTopic model to uncover key themes and pain points from over 14,000 customer tweets, providing actionable insights for airlines.


*The final model identified "Customer Service" as the largest topic, with a predominantly negative sentiment.*

<img width="1178" height="547" alt="sentiment_distribution" src="https://github.com/user-attachments/assets/2bdfa9e3-dcde-420a-8f02-ee682895700c" />


## 🎯 Project Goal

The objective was to move beyond simple sentiment classification and identify the specific *reasons* behind customer satisfaction and dissatisfaction. This was achieved by cleaning unstructured social media text, implementing a topic model, and visualizing the results to highlight key business insights.

---

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:** Pandas, Scikit-learn, Gensim, Plotly, Matplotlib, WordCloud
* **NLP/Modeling:** BERTopic, Sentence-Transformers, Optuna for Hyperparameter Tuning

---

## 📂 Repository Structure
├── Airline_Sentiment_Report.pdf    # Final detailed project report
├── analysis.ipynb                  # Jupyter Notebook with the full analysis
├── wordcloud.png                   # Visualization of key terms
└── sentiment_distribution.png      # Visualization of sentiment per topic

---

## 📈 Key Results & Findings

* The fine-tuned BERTopic model successfully identified **7 distinct topics** with a high coherence score of **0.75**.
* **Customer Service** emerged as the most discussed theme, showing a strong negative sentiment and highlighting a critical area for airline improvement.
* The model achieved a perfect **topic diversity score of 1.0**, confirming that the generated topics were unique and not redundant.

---

## 🚀 How to Run

1.  Clone this repository: `git clone https://github.com/SinanSamah/Airline-Sentiment-Analysis-BERTopic.git`
2.  Create a virtual environment: `python -m venv venv`
3.  Install the required packages: `pip install -r requirements.txt`
4.  Open and run the `analysis.ipynb` notebook.
