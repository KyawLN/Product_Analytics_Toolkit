# Product Analytics Toolkit 🚀

### A Data-Driven Approach to Product Management

**Author:** Kyaw Lwin Naing 
**Role:** Digital Product Business Analyst / Product Owner  
**Tech Stack:** Python, Pandas, TextBlob (NLP)

---

## 📖 Overview
As a Product Owner, prioritizing features and understanding user sentiment can often rely on "gut feeling." This project aims to replace subjective guesswork with **objective data analysis**.

This toolkit demonstrates how Python can be leveraged to:
1.  **Prioritize Roadmaps:** Using a weighted scoring algorithm (Revenue + Demand / Effort) to identify high-ROI features.
2.  **Automate Empathy:** Using Natural Language Processing (NLP) to scan user feedback and instantly flag negative sentiment.

## ⚙️ How It Works

### 1. The Prioritization Engine
Instead of manual RICE scoring, the script ingests raw data (`features.csv`) containing development estimates and projected impact. It outputs a **Value Score** that mathematically balances business value against technical debt.

### 2. The Sentiment Analyzer
The script processes raw user comments (`feedback.csv`) using `TextBlob`. It assigns a polarity score (-1.0 to +1.0) to every comment, allowing product teams to quickly filter for "Critical" (Negative) feedback without manually reading thousands of tickets.
