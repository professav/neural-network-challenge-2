# neural-network-challenge-2

In this week's challenge, I was able to create another neural network. For this activity, this was from an HR perspective where they might want to study why employees leave the company. Also, the company wants to study if a particular department has the affect on the attrition rate, and if the employees might have been better fit for another department. 

I used Google Colab to preprocess, create, compile, and train the model. I chose other columns such as Hourly Rate, Job level, and Years at company to use for the training data. However, data listed in the Hourly Rate is an object and will prove to be difficult to set up in an array against the other data.

In summary, I explained that accuracy would not be the best metric to use for this data. After training the data using a logistic regression model, the accuracy score for Attrition rate was about 85%, whereas the accuracy for Department yielded 0%, mostly because the data may not be consistent. For instance, a person could be in the HR dept, or maybe they are in IT. The data is imbalanced since there could be many departments, it would be difficult to predict that department weighs heavily on the attrition rate. Perhaps the Softmax activation function may be more dependable for the Department data as it would represent the output for each department.

[Click here](https://colab.research.google.com/drive/1ctMRfiSuBRqEtIHTK92TCFHtRIV3MNRj?usp=sharing) to review my code in Google Colab.
