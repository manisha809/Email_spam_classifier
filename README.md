# Email_spam_classifier
## Appendix
Objective: The project aims to develop a user-friendly application for classifying email or SMS messages as either spam or not spam using natural language processing techniques.

Technology Stack: The application is built using Streamlit, a Python library for creating web applications, and leverages pre-trained models stored as pickle files. It utilizes NLTK for text processing, including tokenization, stop word removal, and stemming.

User Interface: The Streamlit app provides a straightforward user interface where users can input a message into a text area. Upon clicking the "Predict" button, the application processes the input and displays the prediction result as a header, indicating whether the message is classified as spam or not.

Text Preprocessing: The text input undergoes preprocessing, including lowercasing, tokenization, removal of stopwords and punctuation, and stemming. These steps aim to transform the input into a standardized format suitable for the machine learning model.

Model Prediction: The application uses a machine learning model, loaded from a pickle file, to predict whether the input message is spam or not. The prediction result is then displayed to the user in a clear and concise manner.


## Application demo: 

![Screenshot (9)](https://github.com/manisha809/Email_spam_classifier/assets/74667664/bd85483f-0f1b-405b-92c2-85d0956e6cef)



Url :    https://emailspamclassifier-mtkzdpcxblw39vwzjvzcwc.streamlit.app/
