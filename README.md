🍽️ Yelp Review NLP & Business Insights (BERTopic + Spark)

Large-scale NLP analysis of Yelp reviews to extract actionable business insights from unstructured text.

📌 Project Overview

This project applies Natural Language Processing (NLP) techniques to millions of Yelp reviews to uncover topic-level drivers of customer satisfaction and dissatisfaction. Using Apache Spark for scalability and BERTopic for topic modeling, the analysis transforms unstructured review text into interpretable, business-relevant insights.

The focus is on extracting themes at scale, linking them to ratings and review volume, and translating NLP outputs into decision-ready signals for businesses.

🎯 Objectives

Process and analyze large-scale unstructured text data

Identify key themes and topics in customer reviews

Link topics to star ratings and performance outcomes

Demonstrate how NLP can support customer experience and operational decisions

📂 Data

Source: Yelp Review Dataset

Volume: 3M+ reviews

Data Type: Unstructured text (customer reviews)

Key Fields Used:

Review text

Star ratings

Business identifiers

Review volume

Data Preparation

Filtered and sampled reviews for scalable modeling

Cleaned and normalized text (lowercasing, noise removal)

Structured data for distributed processing with Spark

🛠️ Methodology
1️⃣ Distributed Text Processing (Apache Spark)

Loaded and processed millions of reviews using Spark

Enabled scalable preprocessing and transformation

Reduced memory and compute bottlenecks

2️⃣ Topic Modeling with BERTopic

Applied BERTopic to extract coherent, interpretable topics

Captured semantic meaning using transformer-based embeddings

Generated topic distributions across reviews

3️⃣ Topic-Level Performance Analysis

Linked topics to:

Average star ratings

Review frequency

Deviation from global rating averages

Identified drivers of satisfaction and pain points at scale

📊 Key Findings

Customer feedback clusters into distinct, interpretable themes (e.g., service quality, wait times, food quality, pricing).

Certain topics are consistently associated with higher or lower star ratings, indicating clear satisfaction drivers.

Topic-level analysis reveals operational issues that may not be visible through average ratings alone.

NLP provides a scalable way to translate qualitative feedback into quantitative business insights.

This project emphasizes insight extraction and interpretability, not sentiment classification alone.

🧠 Business Applications

Identifying what actually drives customer satisfaction

Prioritizing operational improvements (service, speed, quality)

Supporting product, pricing, and staffing decisions

Enhancing review monitoring and customer feedback analysis

This approach mirrors how NLP is used in real-world product analytics, CX analytics, and consulting environments.

🧰 Tools & Technologies

Python

Apache Spark

BERTopic

NLP & ML Libraries:

pandas

NumPy

Transformers / embeddings

Visualization: matplotlib / seaborn
