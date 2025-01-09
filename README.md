# hackathon_humans_lab

Welcome to the **Harnessing Twitter Data for Real-Time Topic Detection and Policy Formulation** repository. This project was developed as part of the **HUMANS Lab: PhD Applicants Hackathon**, aimed at advancing AI-Human-centered computing to address pressing societal issues.

## Table of Contents
- [Project Overview](#project-overview)
- [Repository Structure](#repository-structure)
- [Executable Code](#executable-code)
- [Manuscript](#manuscript)
- [Artifacts](#artifacts)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

## Project Overview

In the realm of contemporary democratic governance, understanding public sentiment in real-time is crucial for effective policy-making. Traditional public opinion polling methods are often hindered by delays, high costs, and limited sample sizes. This project leverages the vast and dynamic nature of Twitter data to overcome these limitations, focusing on the **2024 U.S. Presidential Election** as a case study for analyzing political discourse.

By utilizing Natural Language Processing (NLP) techniques for topic modeling and sentiment analysis, the project identifies key topics and sentiments within the Twitter dataset. Furthermore, it integrates a Large Language Model (LLM), specifically ChatGPT, to translate these insights into actionable policy recommendations aligned with democratic governance principles.

## Repository Structure

```
.
├── README.md
├── hackathon.ipynb
├── hackathon_manuscript.pdf
└── models/
│   ├── tfidf_vectorizer.joblib
│   └── lda_model.joblib    
└── output/
    ├── topics.csv
    └── policy_proposals.txt

```

- **README.md**: This file, providing an overview and instructions for the project.
- **data/**: Contains all datasets used in the project.
  - `df_filtered_lemmatized.csv`: Preprocessed and lemmatized Twitter dataset. You can download [here](https://drive.google.com/file/d/1-2DNvmakOGrnxdo3REGiPGyVilE11D_f/view?usp=sharing)
  - `filtered_data.csv`: Filtered Twitter data based on engagement metrics. You can download [here](https://drive.google.com/file/d/1EmUDQiYkDIfl4SUjc48lJLfdjADX8qUn/view?usp=sharing)
  - `usc-x-24-us-election/`: Directory containing the original 2024 U.S. Election Twitter dataset.
- **hackathon.ipynb**: The executable Jupyter Notebook documenting the entire analysis workflow.
- **hackathon_manuscript.pdf**: The manuscript detailing the research project, methodology, results, and insights.
- **models/**: Stores machine learning models and related artifacts.
  - `tfidf_vectorizer.joblib`: Trained TF-IDF vectorizer used for topic modeling.
  - `lda_model.joblib`: Trained LDA model used for topic modeling.
- **output/**: Stores the output of this work.
- `topics.csv`: Final output of topic modeling.
- `policy_proposals.txt`: Final output of policy generation.

## Executable Code

The core analysis is documented in the `hackathon.ipynb` Jupyter Notebook. You can also run the code by [Google Colab](https://colab.research.google.com/drive/1PshJ5Eoa8fHFkUUT0RBJyAjygzWEY23m?usp=sharing)

## Manuscript

The comprehensive manuscript detailing the research project is available as `hackathon_manuscript.pdf`. 

## Artifacts

The repository includes additional artifacts that support the analysis and findings:

1. **Topic Summaries (`topics.csv`)**
   - Contains top keywords and representative texts for each identified topic.

2. **Policy Proposals (`policy_proposals.txt`)**
   - Generated policy recommendations for each key topic. You can also refer the result via [ChatGPT public link](https://chatgpt.com/share/677fe8bb-3e88-8009-876e-86898624c84b) and [Perprexity public link](https://www.perplexity.ai/search/conduct-a-targeted-search-to-g-V_MV_RK.RPO5X3jT1bXnQw)

3. **Fine-Tuned Models**
   - Any models fine-tuned during the analysis process are stored in the `models/` directory.

## Contact

For any queries or further information, please contact:

**Goshi Aoki**  
Zhejiang University  
Email: [goshi.aoki@icloud.com](mailto:goshi.aoki@icloud.com)

## Acknowledgements

This project was developed as part of the **HUMANS Lab: PhD Applicants Hackathon**. Special thanks to Professor Ferrara and the HUMANS Lab team for providing the datasets and guidelines essential for this research.
