# Projects

 - 1 User Authentication
 
      - **Dataset**: User authentication events. Each time a user logs into a computer (or even possible business applications) an event is created capturing the time, user, and computer that the event occurred on. 
      - **Approach**: Use unsupervised learning (K-means) to try and group users based on their behaviors. 
 
 - 2 Sentiment Analysis
 
      - **Dataset**: Pulling tweets directly from Twitter using their API.
      - **Approach**: Clean up the tweet text & use a labeled dataset (from Kaggle.com) to perform sentiment analysis, identifying which tweets have a positve or negative sentiment related to COVID-19. Then create a clout score for each tweet and plot on a map of the U.S. using the Twitter user's location.

 - 3 Heart Disease Prediction
 
      - **Dataset**: From https://archive.ics.uci.edu/ml/datasets/Heart+Disease
      - **Approach**: Use a (mostly) ready-to-go dataset with heart disease indicators and target. Showcase several supervised learning techniques and explain some advantages/disadvantages. Create a function to use in a real-world scenario to help a cadiology specialist's office workflow.
      
- 4 Network Visualization & Risk Classification

     - **Dataset**: From https://www.kaggle.com/jsrojas/ip-network-traffic-flows-labeled-with-87-apps
     - **Approach**: Use netflow data to cluster nodes by daily aggregates. Visualize network structure with NetworkX package, and highlight the nodes by clusters. Identify nodes that would be prioritized for security hardening and remediation. 
      
- 5 MULTI LABEL CLINICAL NOTE CLASSIFICATION USING BIO CLINICALBERT
     - **Dataset**: From https://www.kaggle.com/c/medical-notes/overview
     - **Approach**: Developed a deep learning model using Bio\_ClinicalBERT to perform multi-label classification of insomnia episodes and contextual durations in clinical notes, achieving 93.5\% accuracy. Compared weak supervision, manual annotation, and LLM-generated labels to build a robust training set. Addressed class imbalance using Binary Cross-Entropy loss and validated performance with F1-micro and F1-macro metrics. Leveraged Google Colab GPUs to accelerate model training, and exported the fine-tuned model to evaluate on unseen clinical notes.

- 6 Schizophrenia (SCZ) Relapse Prediction Case Study
    - **Summary**: This case study highlights a comprehensive approach combining data cleaning, predictive modeling, clinical statistics, and healthcare domain expertise.
    
    - **Dataset**: CMS 2008-2010 Data Entrepreneurs’ Synthetic Public Use File (DE-SynPUF) (dataset with patient encounters, medications, diagnoses, and other clinical records).
    
    - **Data Preparation**:  
      - Cleaned data to identify schizophrenia (SCZ) patients using diagnoses, medications, and encounter records.
    
    - **Modeling Approach**:  
      - Developed multiple machine learning models to predict SCZ relapse events.  
      - Achieved a best model accuracy of **79%**.  
      - Intentionally left the age feature unbalanced to demonstrate differences in interpretability between ML and traditional statistical methods.
    
    - **Statistical Analysis**:  
      - Applied Kaplan-Meier survival curves and Cox proportional hazards models to find meaningful correlations between relapse events and clinical features.
    
    - **Outcomes**:  
      - Produced actionable recommendations from a medical affairs perspective to support patient care and decision-making.
    
- 7 AI-Powered Resume Review Chatbot

  - **Project Overview**: Designed and developed a Flask-based AI chatbot to assist hiring managers with resume reviews and candidate insights.

  - **Tech Stack & Features**:  
    - Built using LangChain, OpenAI API, and transformer models.  
    - Integrated a vector database (Chroma) and embedding techniques for semantic similarity search and retrieval-augmented generation (RAG).  
    - Engineered conversation summarization using a T5-small model to efficiently manage long dialogues.  
    - Optimized token usage and memory management to improve response accuracy and performance within model limitations.

  - **DevOps & CI/CD**:  
    - Set up GitHub Actions for continuous integration (CI), automating testing and quality checks on pull requests.  
    - Enabled faster development cycles and more reliable deployments.

  - **Repository**:  
    - [https://github.com/mitch-gold/MARA](https://github.com/mitch-gold/MARA)
---
 
### If for some reason you cannot view a .ipynb file, please be patient and try reloading. There seems to be an issue viewing this filetype on GitHub sometimes.
