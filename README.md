# 🧠 Discourse and Sentiment Analysis of the Gaza Crisis on Reddit  
### 📊 Academic Research Version — by Basma Mohamed Abu Gheda

---

## 📘 Overview

This repository contains a full academic-style analysis of public sentiment and discourse surrounding the Gaza crisis, using real-time Reddit data. The project combines emotion classification and topic modeling to uncover both the **emotional dynamics** and **thematic structure** of online discussions.

---

## 🎯 Objectives

- Collect Reddit posts related to the Gaza crisis in near-real time  
- Classify emotions using transformer-based models (DistilRoBERTa)  
- Apply unsupervised topic modeling via BERTopic  
- Visualize emotion-topic heatmaps, temporal trends, and representative discourse  
- Build a modular, reproducible, and research-grade analysis pipeline  

---

## 🛠️ Technologies Used

- `Python 3.x`  
- `PRAW` for Reddit API access  
- `Transformers (HuggingFace)`  
- `BERTopic`  
- `Pandas`, `Seaborn`, `Matplotlib`, `Plotly`  
- `Google Colab` (for development)

---

## 📊 Visual Outputs

- Emotion classification across 7 labels (anger, sadness, fear, joy, etc.)  
- Topic modeling with BERTopic and visualized timelines  
- Heatmap: emotion distribution by topic  
- Table: representative Reddit posts per topic  
- Interactive timeline (Plotly)

---

## ⚠️ Known Limitations

- Data limited to Reddit only  
- Hourly refresh pipeline was proposed but not integrated due to Colab scheduling constraints  
- Language limited to English (future work may include multilingual support)

---

## 🔮 Future Work

- Full real-time automation with external scheduler  
- Support for other platforms (Twitter, Facebook)  
- Sentiment trend alerts & summary dashboard  
- Deployment via Streamlit or HuggingFace Spaces  

---

## 👩‍💻 Author

**Basma Mohamed Abu Gheda**  
Data Analyst | NLP Enthusiast | Independent Researcher

[🔗 LinkedIn Profile (optional)](https://www.linkedin.com/in/your-profile)  
📧 basma@email.com (or GitHub contact)

---

## 📄 License

This project is shared under the MIT License — feel free to use, modify, and extend with proper attribution.

---

## 🌍 Acknowledgments

Special thanks to the open-source NLP community, BERTopic developers, and contributors to the Hugging Face models used in this research.
