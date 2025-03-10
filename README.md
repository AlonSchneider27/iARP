# **iARP - Identity Agnostic Reviewer Profiling 📊📝**

## Overview  

### **🔍 The Domain & Problem**  
Peer review is the foundation of academic publishing, ensuring research quality and credibility. However, **reviewer anonymity**—a common practice in conferences and journals—limits our ability to analyze reviewer behavior, detect biases, and ensure fairness in the review process. Traditional profiling techniques rely on explicit reviewer identities, making it challenging to assess reviewing patterns in **anonymous peer review settings**.

Despite the lack of identifiable information, reviewers leave **behavioral footprints** through their review length, acceptance tendencies, sentiment, and confidence scores. These patterns can be leveraged to construct meaningful reviewer profiles without compromising anonymity.

### **🛠️ What & How We Solve It**  
**iARP (Identity Agnostic Reviewer Profiling)** introduces a method to **analyze and profile reviewers** based on **proxy features** extracted from peer review data. Instead of using explicit identities, we derive reviewer characteristics from their review content and decisions. This allows us to:  

- **Assess reviewer tendencies** without requiring personal identifiers.  
- **Identify reviewing styles** using textual and behavioral metrics.  
- **Detect potential biases and inconsistencies** across multiple reviews.  

Our approach extracts **five key features** from peer review datasets and aggregates them into a **radar graph**, offering a structured and interpretable way to profile reviewers.

---

## 📊 Extracted Features for Profiling  

iARP defines **five key features** to profile reviewers:  

1. **Proxy Impact Factor Index** - Estimates a reviewer's impact factor using review length distributions.  
2. **Acceptance Ratio** - Measures the proportion of accepted papers among reviewed submissions.  
3. **Chutzpah (Audacity)** - Evaluates the tendency to reject papers from high-h-index authors.  
4. **Objectivity Confidence** - Combines reviewer confidence scores with text-based objectivity analysis.  
5. **Sentiment Ratio** - Quantifies sentiment polarity of reviews relative to a global benchmark.  

These features are aggregated into a **radar graph** to visually represent reviewer profiles.

---

## 📂 Access Files  

To explore the code, datasets, and visualizations used in this project, visit:  

📂 **GitHub Repository:** [iARP on GitHub](https://github.com/AlonSchneider27/iARP)  
📊 **Project Data:** [Google Drive Link](https://drive.google.com/drive/folders/1hAetSFgm-2hbOmBM03vgu0iYUiEekvc6?usp=sharing)  

---
