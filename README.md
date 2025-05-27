# Mental Health in Tech – Clustering Case Study

This project explores patterns in mental health experiences among technology employees using unsupervised learning techniques. 
The goal is to uncover latent behavioral profiles to support targeted HR and workplace wellness strategies.

## 🧠 Dataset
Survey responses from tech-industry workers, including:
- Demographics (age, gender, country)
- Mental health history
- Workplace support and stigma
- Employer policies and perceptions

## 🧪 Methods
- **Data Cleaning**: Feature engineering, mapping, scaling, and handling missing values using domain-aware logic.
- **Dimensionality Reduction**: PCA used to reduce noise before clustering.
- **Clustering Model**: **HDBSCAN** – Hierarchical Density-Based Clustering

## 📈 Evaluation
- **Silhouette Scores** (full and bootstrapped)
- **One-Way ANOVA** for feature differentiation across clusters
- **VIF Analysis** to check for multicollinearity
- **Correlation Matrix** to check for multicollinearity

## 📊 Outputs
- Cluster horizontal bar charts
- Feature significance visualized with ANOVA and VIF
- Bootstrapped silhouette stability plots

## 📁 Structure
- `mental_health_in_Tech_case_study_report.ipynb`: Main notebook
-  responses.csv dataset
- `README.md`: Overview of the project

## 📌 Goals
Help HR and org leadership:
- Identify hidden patterns
- Tailor mental health initiatives more effectively

## 📚 Techniques Used
`Python`, `Pandas`, `Scikit-learn`, `HDBSCAN`, `Matplotlib`, `Seaborn`
