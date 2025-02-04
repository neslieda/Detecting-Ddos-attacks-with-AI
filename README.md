# Artificial Intelligence in Cybersecurity

This project focuses on the application of artificial intelligence techniques in cybersecurity. Specifically, various machine learning and deep learning models have been employed to detect Distributed Denial of Service (DDoS) attacks. Models such as Long Short-Term Memory (LSTM), XGBoost, Naive Bayes, and Quadratic Discriminant Analysis (QDA) are utilized to detect attacks in network traffic and develop defense mechanisms.

## 📌 Table of Contents
- [General Information](#general-information)
- [Project Objectives](#project-objectives)
- [Technologies Used](#technologies-used)
- [Data Sources](#data-sources)
- [Feature Selection and Descriptions](#feature-selection-and-descriptions)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Performance Comparisons](#performance-comparisons)
- [Results and Discussion](#results-and-discussion)
- [Future Work](#future-work)
- [License](#license)

## 📖 General Information
DDoS attacks are cyber threats aimed at disrupting network systems by overwhelming them with excessive traffic. Traditional detection methods often fall short due to the evolving nature of attacks. AI-powered models can identify threats with higher accuracy and provide faster response mechanisms.

This project develops a model capable of detecting DDoS attacks at an early stage using various machine learning and deep learning algorithms. The effectiveness and performance of these algorithms have been analyzed and compared in detail.

## 🎯 Project Objectives
- Develop an **AI-based system for real-time DDoS detection**
- Compare **different machine learning and deep learning models**
- Achieve **lower false positive rates compared to traditional methods**
- Evaluate the model’s **reliability, scalability, and applicability**

## 🛠️ Technologies Used
The following software tools and libraries were used:
- **Programming Language:** Python 3.9
- **Libraries:**
  - Data processing: Pandas, NumPy
  - Modeling: Scikit-learn, TensorFlow, XGBoost
  - Visualization: Matplotlib, Seaborn
  - Data preprocessing: Scipy, Imbalanced-learn
- **Development Environment:** Jupyter Notebook

## 📂 Data Sources
Three different datasets were used in this study:
1. **Hulk DDoS attacks and normal traffic** (02-16-2018)
2. **HOIC DDoS attacks and normal traffic** (02-21-2018)
3. **DrDoS_NTP attacks and normal traffic** (03-05-2018)

These datasets are pre-labeled and used to distinguish between attack and normal traffic during training.

## 🔍 Feature Selection and Descriptions
The selected features include:
- **Flow-Based Features:** Flow duration, inter-packet arrival times
- **Packet-Based Features:** Total forward and backward packet count, max/min packet length
- **Protocol Features:** TCP flag count, header lengths

## 🏗️ Data Preprocessing
The preprocessing steps include:
- **Data Cleaning:** Handling missing and erroneous values
- **Data Balancing:** Undersampling for minority classes
- **Feature Engineering:** Removing irrelevant features, transformation techniques

## 🔬 Modeling
The following models were evaluated:
- **XGBoost:** Achieved the highest accuracy (**98.6%**)
- **LSTM:** Strong performance in time-series analysis (**97.5%**)
- **Naive Bayes:** Fast but lower accuracy (**74.1%**)
- **QDA:** Balanced performance for mid-scale datasets (**96.8%**)

## 📊 Performance Comparisons
| Model | Accuracy (%) | AUC-ROC |
|--------|------------|---------|
| XGBoost | 98.6 | 99.3 |
| LSTM | 97.5 | 98.9 |
| Naive Bayes | 74.1 | 74.1 |
| QDA | 96.8 | 97.0 |

## 📌 Results and Discussion
XGBoost achieved the highest accuracy, making it the best-performing model. LSTM was effective in time-series-based analysis. Compared to traditional methods, AI-based models reduce false positive rates and provide more reliable results.

## 🚀 Future Work
- **Enhancing accuracy with hybrid models**
- **Developing real-time attack detection systems**
- **Integrating with mobile and cloud platforms for scalability**

## 📜 License
This project is licensed under the [MIT License](LICENSE). Contributions to improve the project are encouraged.
