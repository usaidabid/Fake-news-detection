# Fake-news-detection

 1 : The approach used:
 
 The fake news detection model was built using machine learning techniques. The dataset was preprocessed by cleaning text, removing stopwords, and converting it into numerical form using TF-IDF vectorization. A Naive Bayes model was trained on the processed data to classify news articles as real or fake. After training, the model was saved and deployed using Flask, allowing users to enter a news article and get a prediction.
 
 2: Challenges faced:
 
 One of the main challenges was handling imbalanced data, as there were more real news articles than fake ones. Another challenge was optimizing the model's accuracy while preventing overfitting. Additionally, deploying the model and integrating it into a user-friendly interface required debugging and adjustments to ensure smooth functionality.

 3: Model performance & improvements:
 
The Naive Bayes model achieved a good accuracy in detecting fake news, but there is room for improvement. Using deep learning techniques like LSTMs or transformers could enhance the model’s ability to detect more complex patterns in text. Further improvements could include training on a larger dataset and fine-tuning hyperparameters for better performance.

Check it out :
https://huggingface.co/spaces/usaid123/usaid-fake-news-detector
