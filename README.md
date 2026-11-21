###Mapping Philippine Grad School Talk: PCA, Regression & Big Four Reply Dynamics

📌 Overview

This project provides a data-driven exploration of graduate school discussions within the Philippine Reddit community (specifically r/gradschoolph). By leveraging natural language processing, Principal Component Analysis (PCA), and regression modeling, this study maps common themes, evaluates user engagement, and analyzes reply dynamics across top Philippine institutions ("Big Four").

💡 Inspiration

This project was inspired by Simon Ezekiel Mariquit's analytical work using the Reddit API ("What do UPLB students ask on Reddit, and which questions does nobody answer? I pulled two years of r/peyups, r/uplb and r/upelbi to find out."). Building upon that premise, this repository extends the lens toward postgraduate studies and university-level interaction dynamics in the Philippines.

📁 Repository Structure

├── Datasets/
│   └── Dataset.txt                                                        # Cleaned and processed Reddit datasets
├── Notebooks/
│   └── Mapping_Philippine_Grad_School_Talk_PCA,_Regression_&_Big_Four_Reply_Dynamics.ipynb  # Primary exploratory & modeling notebook
├── Presentation/
│   ├── r_gradschoolph Analytical Summary & Key Findings Report.pdf        # Comprehensive executive report
│   └── rgradschoolph PCA Study.pdf                                        # Slides focusing on the PCA methodology & clusters
└── README.md                                                              # Project documentation


🔑 Key Features & Methodology

Data Collection & Preprocessing

Extracted sub-reddit posts and comment trees using the Reddit API.

Cleaned text data (tokenization, stop-word removal tailored to Taglish/Philippine academic lingo).

Dimensionality Reduction (PCA)

Grouped high-dimensional text feature vectors to isolate core discussion themes (e.g., admission inquiries, thesis stress, working-student balances, institutional comparisons).

Regression & Reply Dynamics Analysis

Modeled factors influencing post visibility and response rates (e.g., post length, time of posting, university affiliation mentions).

Examined comment engagement patterns across mentions of the "Big Four" universities (UP, ADMU, DLSU, UST).

📊 Key Artifacts & Reports

Detailed summaries and visualizations can be found in the Presentation/ directory:

r_gradschoolph Analytical Summary & Key Findings Report.pdf: In-depth analytical write-up outlining statistical models, hypothesis tests, and insights.

rgradschoolph PCA Study.pdf: Visual representation of the principal components and topic clustering results.

🚀 Getting Started

Prerequisites

Ensure you have Python 3.8+ installed along with the following packages:

pip install pandas numpy matplotlib seaborn scikit-learn jupyter


Running the Notebook

Clone this repository:

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name


Launch Jupyter Notebook:

jupyter notebook Notebooks/Mapping_Philippine_Grad_School_Talk_PCA,_Regression_&_Big_Four_Reply_Dynamics.ipynb


🤝 Acknowledgments

Simon Ezekiel Mariquit — for the original conceptual inspiration regarding Reddit API data extraction and question responsiveness analysis within the UP community (r/peyups, r/uplb, r/upelbi).

📜 License

Distributed under the MIT License. See LICENSE for more information.
