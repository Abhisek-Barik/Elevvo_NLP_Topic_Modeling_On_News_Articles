# 💬 NLP Task 5 – Topic Modeling on News Articles  

## 🚀 ELEVVO Internship | Abhisek Barik  
### 🌟 Level-2 → NLP Task 5 ✅ + Bonus 💡 Completed  

---

## 📌 Task Description  
Discover hidden topics or themes in a collection of news articles (BBC dataset) using **Latent Dirichlet Allocation (LDA)** and **Non-negative Matrix Factorization (NMF)**. Visualize topic distributions and compare performance using both classic modeling and visual tools.

---

## 📂 Dataset  
- **Source**: BBC News Dataset 📰  
- **Format**: Text data across various news categories (e.g., politics, tech, business)  
- **Target**: No labels — **unsupervised learning** task  

---

## 🧰 Tools & Libraries Used  
- 🐍 Python  
- 📊 Pandas, NumPy  
- ✂️ NLTK (Text Preprocessing)  
- 🧠 Gensim (LDA Model)  
- 📈 Scikit-learn (NMF Model)  
- 🌐 pyLDAvis (Interactive Topic Visualization)  
- ☁️ WordCloud (Bonus Visualization)  

---

## 🔄 Workflow Steps

### ✅ 1. Data Loading & Preprocessing  
- Converted text to lowercase 🔡  
- Tokenized and removed stopwords 🛑  
- Cleaned text for LDA compatibility  

### 📘 2. Dictionary & Corpus Creation  
- Used `gensim.corpora.Dictionary`  
- Created document-term matrix (Bag-of-Words)  

### 🧠 3. Topic Modeling – LDA  
- Trained LDA model with:
  - `num_topics=5`
  - `passes=10`
  - `chunksize=100`  
- Displayed top 10 keywords per topic  

### 📊 4. Topic Modeling – NMF (BONUS)  
- Used `TfidfVectorizer` for feature extraction  
- Applied NMF to get alternate topic groupings  
- Compared performance vs LDA  

### 📈 5. Visualizations  
- **pyLDAvis**: Interactive topic visualization 🔍  
- **WordClouds**: Displayed high-weight topic words ☁️  

---

## 🎁 BONUS SECTION  

### 🎁 Bonus 1: Compare LDA vs NMF  
| Model | Vectorizer | Output |  
|-------|------------|--------|  
| 🧠 LDA | BoW | 5 Topics with distinct distributions |  
| 📘 NMF | TF-IDF | 5 Topics with different word focuses |  

### 🎁 Bonus 2: WordClouds  
- 🌀 Used WordCloud to visually compare topic themes  
- Enhanced understanding of word significance in topics  

---

## 📚 Concepts Covered  
- 🔍 Topic Modeling  
- 🛠️ Text Cleaning & Preprocessing  
- 🔢 Feature Extraction (BoW & TF-IDF)  
- 🤖 Unsupervised Learning  
- 📈 Model Visualization & Comparison  
