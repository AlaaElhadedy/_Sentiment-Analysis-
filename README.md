

## 🔗 Live Demo
👉 [افتح الداش بورد هنا](https://sentiment-dashboard-gvh5j33d0-alaaelhadedys-projects.vercel.app/)

## 📌 عن المشروع
مشروع NLP كامل لتحليل وتصنيف مشاعر المراجعات باستخدام بيانات 568,454 مراجعة حقيقية من Amazon Food Reviews.

## 🎯 المشكلة
الشركات محتاجة تفهم رأي العملاء في منتجاتها بشكل سريع وتلقائي. المشروع ده بيحاول يصنف أي مراجعة كـ Positive أو Negative باستخدام تقنيات NLP و Deep Learning.

## 🛠️ التقنيات المستخدمة
- 🐍 Python (Pandas, NumPy, Scikit-Learn, NLTK)
- 🔤 NLP (TF-IDF, Word Cloud, Text Cleaning)
- 🧠 PyTorch (LSTM Deep Learning)
- ⚛️ React & Recharts
- 🌐 Vercel

## 📊 مراحل المشروع

### 1️⃣ Data Cleaning
- تنظيف النصوص من HTML tags والأرقام والـ punctuation
- إزالة الـ Stop Words باستخدام NLTK
- تحويل الـ Score (1-5) لـ Positive/Negative

### 2️⃣ EDA & Feature Engineering
- تحليل توزيع الـ Sentiment (84.4% Positive)
- Word Cloud للكلمات الأكثر تكراراً
- TF-IDF Vectorizer بـ 10,000 feature

### 3️⃣ Machine Learning
- Naive Bayes ✅ أفضل نموذج بـ F1: 0.932
- LSTM (Deep Learning) بـ F1: 0.874

### 4️⃣ Dashboard
- 5 رسوم بيانية تفاعلية
- Sentiment Predictor مع Word Highlighting
- Prediction History
- Mobile Responsive

## 📈 النتائج
- أفضل نموذج: **Naive Bayes + TF-IDF**
- نسبة المراجعات الإيجابية: **84.4%**
- أكثر الكلمات تكراراً في الإيجابي: good, great, love, delicious
- أكثر الكلمات تكراراً في السلبي: bad, terrible, waste, expired

## 📁 محتوى الـ Repository
- `sentiment_analysis.ipynb` — كود الـ Data Science كامل
- `sentiment_distribution.csv` — توزيع الـ Sentiment
- `sentiment_model_results.csv` — نتائج النماذج
- `sentiment_sample.csv` — عينة من الداتا
- `top_words.csv` — أهم الكلمات لكل Sentiment
