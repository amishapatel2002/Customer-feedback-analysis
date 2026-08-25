# Sentiment Analysis using Python and TextBlob

## 📌 Project Overview

This project focuses on performing **Sentiment Analysis on textual data** using Python and Natural Language Processing (NLP).

The project uses **TextBlob** to analyze the sentiment polarity of text sentences and classify them into different sentiment categories. The processed results are then analyzed using Python and visualized to understand the overall sentiment distribution.

The project was developed and executed in a **Jupyter Notebook** environment.

## 🎯 Objectives

* Perform sentiment analysis on text data.
* Use NLP techniques to determine the polarity of sentences.
* Classify text into Positive, Negative, and Neutral sentiment categories.
* Analyze the frequency of each sentiment category.
* Visualize sentiment distribution using a pie chart.
* Gain practical experience with text-based data analysis.

## 🛠️ Technologies & Libraries

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **TextBlob** – Natural Language Processing and sentiment analysis
* **Matplotlib** – Data visualization
* **Seaborn** – Visualization support
* **Jupyter Notebook** – Project development environment

## 🔍 Project Workflow

### 1. Import Required Libraries

The project imports Pandas, NumPy, Matplotlib, Seaborn, and TextBlob for data processing, sentiment analysis, and visualization.

### 2. Load and Explore the Text Data

The dataset contains a **`Sentences`** column containing textual feedback/comments that are analyzed for sentiment.

### 3. Apply Sentiment Analysis

TextBlob is used to calculate the sentiment polarity of each sentence. A sentiment-analysis function is applied to the `Sentences` column, and the resulting classification is stored in a new **`sentiment`** column.

### 4. Sentiment Classification

The project categorizes the text based on sentiment polarity into:

* **Positive**
* **Negative**
* **Neutral**

The resulting dataset contains both the original sentence and its corresponding sentiment classification.

### 5. Sentiment Distribution Analysis

The `value_counts()` function is used to calculate the frequency of each sentiment category.

### 6. Data Visualization

A **pie chart** is created to visualize the distribution of the sentiment categories and make the results easier to interpret.

## 📊 Key Analysis

The project converts unstructured textual information into structured sentiment categories, making it easier to analyze customer/user opinions at an overall level.

The analysis demonstrates how NLP can be used to transform text data into meaningful analytical information.

## 💡 Business Applications

Sentiment analysis can be useful for:

* Customer feedback analysis
* Product and service reviews
* Social media monitoring
* Customer experience analysis
* Brand perception analysis
* Identifying positive and negative feedback
* Supporting data-driven business decisions

## 🚀 Future Improvements

The project can be further enhanced by:

* Performing text preprocessing such as removing stopwords and punctuation.
* Adding word-frequency analysis.
* Creating WordCloud visualizations.
* Performing sentiment analysis by topic or category.
* Comparing different NLP sentiment-analysis techniques.
* Building an interactive **Power BI dashboard** from the processed results.
* Using advanced NLP models for more accurate sentiment classification.

## 📂 Project Structure

```text
Sentiment-Analysis/
│
├── Sentiment Analysis project.html
├── dataset.csv
├── README.md
└── visualizations/
```

## 👩‍💻 Skills Demonstrated

**Python | NLP | Sentiment Analysis | TextBlob | Pandas | NumPy | Data Visualization | Matplotlib | Seaborn | Jupyter Notebook | Exploratory Data Analysis**

## 📌 Conclusion

This project demonstrates the practical application of **Natural Language Processing and Data Analytics** to extract sentiment from textual data. By classifying sentences into sentiment categories and visualizing their distribution, the project shows how unstructured text can be transformed into useful analytical insights.
