# microfinance_services_ML
Microfinance Services: Using Machine Learning to Predict Feasibility in Kenya - Code and Paper 

During my time at the Chinese University ok Hong Kong I had the chanche to improve my data science skills through different courses. Among them, an advanced economics model that had me using machine learning to make predictions on a topic of choiche. For my final paper, I decided to use machine learning in Python to predict microfinance services performance using the following Kaggle dataset with data from Kenya: Kinuthia, R. (2018). Islamic Microfinance Services Feasibility Study. Retrieved from https://www.kaggle.com/datasets/rkinuthia/islamic-microfinance-services-feasibility-study. 

My paper investigates usage of informal Kenyan microfinance investment groups, known as chamas, and based on this, to analyse the feasibility of implementing a web application to assist in chama organisation and management. A population survey provides information on current usage of these groups, which was used to train predictive models. Two logistic regression models, one selecting its variables with a hyperparameter tuning and the other one by p-value significance, and a neural network using variables with p-value significance, were trained on the survey results to predict chama usage. Model performance was evaluated and compared using confusion matrices and accuracy. The results show that the first logistic regression is very accurate, with a test accuracy of 1 and a train accuracy 0.95. Such a high train accuracy suggests that the model performs well on unseen data and may not be overfitting. The second logistic regression does not perform as well, with a test accuracy score of 0.37. To investigate such a low accuracy, the paper uses a neural network analysis on the same variables. As expected, the neural network performs much better, with an accuracy score of 0.84. The study demonstrates the potential of using advanced analytics to improve the understanding and use of chama microfinance services in Kenya. The paper focuses on an unrepresented and vastly unbanked part of potential microfinance clients, the Muslim population. The study shows that belonging to the Christian religion may influence the decision of joining an informal microfinance chama group, but Muslim religion appears to be less significant with a p-value of 0.067. Understanding these factors could help to optimise the financial performance of microfinance initiatives in Kenya and similar contexts. Conclusively, digitalizing the processes of microfinance in Kenya through a digital platform for managing savings groups is worth exploring further, as it has the potential to make microfinance services more accessible and to create revenue. Making such an app for a sharia compliant population is also worth exploring, as the p-value for the Muslim religion variable is barely not significant.
