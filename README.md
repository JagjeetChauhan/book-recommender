# 📚 Book Recommender

Welcome to **Book Recommender**, a powerful book recommendation system built using **Hugging Face**, **LangChain**, **Gradio**, and the **Kaggle 7K dataset**. This project utilizes the **all-MiniLM-L6-v2** embedding model and leverages **vector search**, **text classification**, and **sentiment analysis** to provide personalized book recommendations.

---

## 🚀 Features

- 🔍 **Intelligent Book Recommendations** using vector search
- 📊 **Pattern Analysis** on missing data and category distribution
- ✂️ **Text Processing** with CharacterTextSplitter
- 🏛 **Vector Database** for efficient similarity search
- 🤖 **Book Classification** using machine learning models
- 🎯 **Sentiment Analysis** of book descriptions using **j-hartmann/emotion-english-distilroberta-base**
- 💻 **Gradio Dashboard** for interactive book recommendations

---

## 🧰 Technologies Used

- **Kaggle 7K Dataset** for book data
- **Hugging Face** for pre-trained models (all-MiniLM-L6-v2 for embeddings)
- **LangChain** for building vector databases and processing text
- **Gradio** for creating an interactive web dashboard
- **Scikit-learn** for machine learning models
- **j-hartmann/emotion-english-distilroberta-base** for sentiment analysis

---

## 📋 Project Workflow

### 1. **Data Preprocessing**
   - **Patterns of Missing Data**: We analyze and handle any missing data in the dataset.
   - **Check the Number of Categories**: We inspect the distribution of categories in the dataset.
   - **Remove Short Descriptions**: Short descriptions are filtered out to ensure quality data for recommendation.

### 2. **Text Processing**
   - **Splitting Books Using CharacterTextSplitter**: We split long book descriptions into smaller chunks for better processing.

### 3. **Vector Database Construction**
   - **Building the Vector Database**: Using the **all-MiniLM-L6-v2** model, we generate embeddings and store them in a vector database for efficient search.

### 4. **Book Recommendations**
   - **Getting Book Recommendations Using Vector Search**: We perform a similarity search in the vector database to recommend books based on the user's input.

### 5. **Text Classification**
   - **Classifying Book Descriptions**: Using machine learning, we classify book descriptions into predefined categories.
   - **Accuracy Check**: The model achieved an accuracy of around 80% in classifying book descriptions.

### 6. **Sentiment Analysis**
   - **Fine-Tuning LLMs for Sentiment Analysis**: We explore fine-tuned models for sentiment analysis to extract emotions from book descriptions using the **j-hartmann/emotion-english-distilroberta-base** model.

### 7. **Interactive Dashboard**
   - **Building a Gradio Dashboard**: A user-friendly interface is built using **Gradio** to allow users to interact with the recommender system and get book suggestions.

---
