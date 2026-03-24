<div align="center"> 
  <h1>Data Science Portfolio</h1>
  <h3>by Nathaniel Jonathan Rusli</h3>
  
  ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
  ![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
  ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
  ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
  ![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
  ![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
  ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
  ![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge&logo=xgboost&logoColor=white)
  ![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=for-the-badge&logo=catboost&logoColor=black)
  ![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=for-the-badge&logo=lightgbm&logoColor=white)
  ![SHAP](https://img.shields.io/badge/SHAP-FF6B6B?style=for-the-badge&logo=python&logoColor=white)
  ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
  ![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)
  ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
  ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
  ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

## Welcome!

This portfolio repository showcases my notable data science projects in the domains of **machine learning**, **deep learning**, **statistical modeling and testing**, **data visualization**, and **data storytelling**. I also included data and business consulting projects, some of which have won case competitions and they will better highlight my data visualization and storytelling skills. Several projects featured here are from competitions I joined, university projects, and external courses I completed.

**Contact Information:**
* **LinkedIn:** [Nathaniel Jonathan Rusli](https://www.linkedin.com/in/nathanieljr/)
* **Email:** omgitsnathaniels@gmail.com

---

## Achievements

* **[International, 2025]** Outstanding Student of Global Consumer Intelligence Course (Top 21 out of 7,724)
* **[National, 2026]** 2nd Winner of ARA Data Science Competition
* **[National, 2025]** 1st Winner of Informatics Festival Data Analysis Competition
* **[National, 2025]** 5th Place Finalist of Logika UI Data Science Competition
* **[National, 2025]** Top 5 Finalist of Investment Festival Equity Research Competition
* **[National, 2025]** 1st Winner of Talent Growth x MarkPlus National Business Case Competition
* **[National, 2024]** 1st Winner of StudentsxCEOs Global Summit Business Case Competition
* **[National, 2024]** Bakti BCA Scholarship Awardee

---

## Projects

### 1. [Pothole Semantic Segmentation with EoMT](Pothole%20Semantic%20Segmentation%20with%20EoMT/)

**Description:** Built a complete end-to-end pothole semantic segmentation pipeline using the **Encoder-only Mask Transformer (EoMT)** as the primary model, with a ViT-Large backbone pre-trained via DINOv3 Masked Image Modeling. The project covers in-depth EDA (sharpness with Laplacian Variance, brightness with Mean Pixel Intensity, spatial centroid with Image Moments, pixel density, and pothole scale profiling), stratified data splitting, geometric-only augmentation strategy, custom Dice + BCE loss, objectness-weighted query aggregation, and Test-Time Augmentation (TTA) with flip-based ensembling for more robust inference.

**Key Areas:**
* Computer Vision & Semantic Segmentation
* Vision Transformers (ViT) & Transfer Learning
* Fine-Tuning & Custom Loss Design
* Test-Time Augmentation (TTA)

**Role:** data exploration and auditing, preprocessing and augmentation, modeling and experiments, loss design, TTA inference, visualizations, slide building

**Technologies:** PyTorch, EoMT-DINOv3 (Hugging Face Transformers), albumentations, OpenCV, PIL, scikit-learn, pandas, NumPy, matplotlib

**Results:** Achieved competitive Dice Coefficient segmentation performance using EoMT-DINOv3 (eomt-dinov3-ade-semantic-large-512) fine-tuned on the pothole dataset with stratified validation and TTA inference. *This project was submitted for ARA 7.0 Data Science Competition, finished 2nd place (national)*

---

### 2. [Cultural Image Classification with DINOv3 & XAI](Cultural%20Image%20Classification%20with%20DINOv3%20&%20XAI/)

**Description:** Implemented state-of-the-art DINOv3 (Huge variant) model for cultural image classification with explainable AI techniques. The project includes comprehensive EDA, feature extraction using facebook/dinov3-vith16plus-pretrain-lvd1689m, custom classification head design, and hyperparameter tuning to achieve optimal performance.

**Key Areas:**
* Deep Learning & Computer Vision
* Transfer Learning
* Fine Tuning
* Explainable AI (XAI)

**Role:** image preprocessing, modeling and experiments, visualizations, xai, data validaiton, paper writing

**Technologies:** PyTorch, DINOv3, Transformers (Hugging Face), CNN, OpenCV, PIL, torchvision, scikit-learn, PIL

**Results:** Successfully implemented DINOv3-Huge model with custom classification head and comprehensive model evaluation metrics. *This project was submitted for Logika UI (Universitas Indonesia) Data Science Competition, finished 5th place (national)*

---

### 3. [IBM Employee Churn Data Consulting](IBM%20Employee%20Churn%20Data%20Consulting/)

**Description:** Comprehensive data consulting project analyzing IBM HR Analytics Employee Attrition & Performance dataset with over 44 features and 1,470 entries. Developed predictive models to identify key factors driving employee churn and provided actionable business recommendations. Project completed as the final assignment for Global Consumer Intelligence Course (GCIC).

**Key Areas:**
* Predictive Analytics & Machine Learning
* Exploratory Data Analysis (EDA)
* Data Visualization & Storytelling
* Business Intelligence

**Technologies:** Python, pandas, NumPy, scikit-learn, CatBoost, matplotlib, seaborn, hvPlot

**Results:** Delivered data-driven insights on employee attrition patterns and factors, with interactive visualizations for stakeholder presentations.

---

### 4. [Movie Popularity Analysis with ML, DL & Statistics](Movie%20Popularity%20Analysis%20with%20ML,%20DL%20&%20Statistics/)

**Description:** Multi-faceted analysis of movie popularity combining machine learning, deep learning, and statistical methods. Implemented regression models (XGBoost, CatBoost), NLP techniques (TF-IDF, Sentence Transformers), and statistical hypothesis testing (Spearman correlation, Mann-Whitney U, Kruskal-Wallis) to predict and explain movie popularity factors.

**Key Areas:**
* Machine Learning (Regression & Classification)
* Natural Language Processing (NLP)
* Statistical Inference & Hypothesis Testing

**Role:** modeling, statistical testing, data visualization, data storytelling

**Technologies:** Python, XGBoost, CatBoost, IndoBERT, Sentence Transformers, scikit-learn, statsmodels, scipy, pandas, matplotlib, seaborn

**Results:** Built comprehensive predictive models with high accuracy, identified statistically significant factors affecting movie popularity. *This project was submitted for Informatics Festival Unpad (Universitas Padjadjaran) Data Analysis Competition, finished 1st place (national)*

---

### 5. [Talent Salary Prediction](Talent%20Salary%20Prediction/)

**Description:** Advanced machine learning solution for predicting talent salaries in the data analytics industry. Implemented ensemble methods (CatBoost, XGBoost, LightGBM) with extensive feature engineering, K-Fold cross-validation, and SHAP values for model interpretability. Team project that secured 1st place in a national business case competition.

**Key Areas:**
* Regression Modeling & Ensemble Methods
* Feature Engineering & Selection
* Model Interpretability (SHAP)
* Cross-Validation Strategies

**Role:** feature engineering, modeling and experiments, visualizations, shap, data visualization, paper writing

**Technologies:** Python, CatBoost, XGBoost, LightGBM, SHAP, scikit-learn, pandas, NumPy, matplotlib, seaborn

**Results:** Achieved high prediction accuracy (low MAE) through ensemble modeling and hyperparameter optimization with model generalization (finished 6th on public leaderboard and 3rd on private leaderboard).
*This project was submitted for Informatics Festival Unpad (Universitas Padjadjaran) Data Analysis Competition, finished 1st place (national)*

---

### 6. [Monte Carlo Simulation for Stock Valuation](Monte%20Carlo%20Simulation/)

**Description:** Implemented Monte Carlo simulation (10,000 iterations) for Sum-of-the-Parts (SOTP) stock valuation, combining Discounted Cash Flow (DCF) analysis and Enterprise Value multiples. The simulation accounts for uncertainty in key financial parameters (WACC, growth rate, EV/EBIT multiples, holding discount) to generate probabilistic valuation distributions.
*This project was submitted for Investment Festival ITB (Institut Teknologi Bandung) Equity Research Competition, finished 4th place (national)*

**Key Areas:**
* Monte Carlo Simulation
* Financial Modeling (DCF & Multiples)
* Probability & Statistics
* Risk Analysis & Quantitative Finance

**Technologies:** Python, NumPy, pandas, matplotlib

**Results:** Generated 10,000 simulated fair value projections with statistical distributions, enabling data-driven investment decisions under uncertainty. Applied as part to Investment Festival Equity Research Competition (Top 5 Finalist).

---

### 7. [Business Case Competitions](Business%20Case%20Competitions/)

**Description:** Collection of winning business case competition projects demonstrating data analytics, strategic thinking, and business storytelling capabilities. Projects include market analysis, consumer insights, competitive intelligence, and data-driven strategy recommendations.

**Key Areas:**
* Business Analytics & Strategy
* Data Storytelling & Presentation
* Market Research & Consumer Insights
* Competitive Analysis

**Role:** data research, data analysis, data visualization, data storytelling

**Results:** 
* 1st Winner - Talent Growth x MarkPlus National Business Case Competition (2025)
* 1st Winner - StudentsxCEOs Global Summit Business Case Competition (2024)

---

## Core Competencies

**Technical Skills:**
* **Machine Learning:** Supervised Learning (Regression, Classification), Unsupervised Learning, Ensemble Methods, Hyperparameter Tuning, etc.
* **Deep Learning:** Transfer Learning, Fine Tuning, Computer Vision, Basic NLP
* **Statistics:** Probability Theory, Statistical Inference, Hypothesis Testing, Stochastic Processes
* **Mathematics:** Calculus, Linear Algebra, Optimization Theory
* **Data Analysis:** EDA, Feature Engineering, Data Preprocessing, Data Visualization
* **Database & SQL:** Database Design (Normalization, BCNF), Database Management Systems (DBMS), Query Optimization, Complex SQL Queries, Relational Database Modeling, ETL/ELT Concepts
* **Programming:** Python, SQL, C, C++, Java, JavaScript, HTML, CSS
* **Tools & Libraries:** PyTorch, TensorFlow, scikit-learn, pandas, NumPy, matplotlib, seaborn, XGBoost, CatBoost, LightGBM, SHAP

**Soft Skills:**
* Data Storytelling & Business Communication
* Strategic Thinking & Problem Solving
* Team Collaboration & Leadership
* Research & Documentation

---

## Certifications

### [Deep Learning Specialization](https://www.coursera.org/account/accomplishments/specialization/1YRRMJVWY97X) - DeepLearning.AI
* [Neural Networks and Deep Learning](https://www.coursera.org/account/accomplishments/verify/W3WQYCCPQJJD)
* [Improving Deep Neural Networks: Hyperparameter Tuning, Regularization and Optimization](https://www.coursera.org/account/accomplishments/verify/XKP2YUWIHZE7)
* [Structuring Machine Learning Projects](https://www.coursera.org/account/accomplishments/verify/3WG65QJE5QGL)
* [Convolutional Neural Networks](https://www.coursera.org/account/accomplishments/verify/ZRYRNMLO881D)
* [Sequence Models](https://www.coursera.org/account/accomplishments/verify/LY4HVGUMF38X)

### [Machine Learning Specialization](https://www.coursera.org/account/accomplishments/specialization/KLEJ2JNX83UB) - Stanford University & DeepLearning.AI
* [Supervised Machine Learning: Regression and Classification](https://www.coursera.org/account/accomplishments/verify/3EWVRDR2E9KA)
* [Advanced Learning Algorithms](https://www.coursera.org/account/accomplishments/verify/G8BVCEZYSRNE)
* [Unsupervised Learning, Recommenders, Reinforcement Learning](https://www.coursera.org/account/accomplishments/verify/CAB0RF4JMSW9)

### Other Certifications
* [Global Consumer Intelligence (GCI) Global 2025]() - Matsuo-Iwasawa Lab University of Tokyo
* [Introduction to Financial Engineering and Risk Management](https://www.coursera.org/account/accomplishments/verify/EWJZ21IHHKQB) - Columbia University
* [CS50's Introduction to Programming with Python](https://certificates.cs50.io/a79b3f82-7a4d-4a48-b37f-4f3abf1918bb.pdf?size=letter) - Harvard University
* [CS50x Introduction to Computer Science](https://certificates.cs50.io/705606de-ff53-4e7f-a400-19b6195f6759.pdf?size=letter) - Harvard University

---

<div align="center">
  <i>Thank you for visiting my portfolio! Feel free to reach out for collaborations or opportunities.</i>
</div>