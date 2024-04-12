![1_iuoT4P9L802xZPg0x1oGgA](https://github.com/anujthakur5592/Web-Mining-Project/assets/166769513/1267dc88-bd9a-42ea-abce-ce4fd620c6de)

# Natural Language Processing with Disaster Tweets
During crises, social media provides vast information, including event details, emotions, and relief efforts. This project proposes a natural disaster analysis interface relying solely on Twitter tweets. Real-time tweets are collected to build a sentiment classifier for gauging users' feelings towards the event's severity. The primary aim is distinguishing genuine tragedies from non-events. Various NLP techniques will be explored, feeding features into classifiers like ridge, Naive Bayes, SVM, and LSTM models. Automation via social media data is suggested. The project demonstrates a novel application for understanding crisis impacts via user-generated tweets. It facilitates discerning trustworthy disaster-related tweets and detecting real crises promptly, aiding both people and government agencies. Furthermore, it supports the development of a more precise disaster tweet classifier.
# Background and Related Work
![495116_1_En_46_Fig1_HTML](https://github.com/anujthakur5592/Web-Mining-Project/assets/166769513/eefda0ee-7fdc-44ce-b22f-f569b11bd864)

Over the past decade, social media platforms like Twitter, Instagram, Facebook, and Snapchat have witnessed an unprecedented surge in user-generated unstructured data (Agarwal et al., 2011). Users utilize these platforms to express opinions, discuss issues, and share grievances, presenting businesses with an opportunity to leverage sentiment analysis for applications such as marketing, crisis management, and political campaigns (Çeliktuğ, 2018). Sentiment analysis holds significance in disaster relief, allowing immediate mobilization of response teams based on social media posts near disaster zones. However, distinguishing genuine catastrophes from metaphorical or humorous content poses a challenge for algorithms (Kaggle, 2021). Verma et al. (2011) integrated natural language processing with Naive Bayes and Maximum Entropy algorithms to identify situational awareness tweets during crisis events. Tan et al. (2009) proposed a weighted Naive Bayes classifier coupled with the Expectation-Maximization (EM) algorithm for sentiment analysis, iteratively transferring weights between source and target domains until convergence.
# Algorithms and Models Used
![futureinternet-13-00163-g001](https://github.com/anujthakur5592/Web-Mining-Project/assets/166769513/792c5de5-848e-415f-a8c5-5fb5b2918de8)

SVM - LinearSVC: Used for binary classification, tuning 'C' and 'penalty' balances margin width and misclassifications. 'C' controls margin width, favoring wider margins with smaller values. 'Penalty' adds regularization, exploring L1/L2 penalties.
Multinomial NB: Probabilistic classifier for text, assumes feature independence. Tuning 'alpha' handles unseen features, with higher values for more smoothing.
Logistic Regression: Linear model estimating class probability. Parameters 'C', 'penalty', and 'max_iter' adjusted. 'C' balances regularization and fitting, 'penalty' offers L1/L2 options, and 'max_iter' specifies convergence iterations.
![Untitled](https://github.com/anujthakur5592/Web-Mining-Project/assets/166769513/43ed890d-4acb-4c59-9b71-16050abda873)

# Conclusion: 
Our project lays the groundwork for effective disaster-related tweet analysis, with future work focusing on advanced models, feature engineering, real-time monitoring, and research on social media language patterns.
By continually refining and expanding these approaches, we aim to contribute to improved disaster response and community resilience in the face of emergencies.
Overall, our efforts aim to leverage data-driven insights to enhance disaster management strategies, ultimately benefiting society as a whole.
