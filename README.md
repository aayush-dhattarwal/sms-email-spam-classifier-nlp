# email-sms-spam-classifier-nlp
The SMS/Email spam classifier project is designed to identify spam messages from genuine (not spam) ones. It utilizes a SMS spam collection dataset obtained from Kaggle, which contains a collection of SMS messages labeled as spam or ham. The project is built using various Natural Language Processing (NLP) libraries available in the Natural Language Toolkit (NLTK) in Python. The first step in the project is to perform exploratory data analysis (EDA) on the dataset to gain insights into the data, including the distribution of the messages, the frequency of spam and non-spam messages, and the most common words used in spam messages. This is done in Jupyter notebook, which allows for interactive analysis and visualization of the data. After EDA, feature engineering is done which includes adding various columns like number of words, sentences, etc to make the prediction better. Finally, the Multinomial Naive Bayes model is selected to classify SMS/Email messages as spam or not spam due to it hifg accuracy at ~97% and highest precisopn among the various algorithms tested on the dataset. Streamlit is used for Backend.
# Dataset used
https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset
# Live Demo
https://aayush-dhattarwal-sms-email-spam-classifier-nlp-app-lnvz48.streamlit.app/
# Screenshots
![chrome_VFrYgR0qVA](https://user-images.githubusercontent.com/29508011/226755254-8284b7d2-902d-48d7-9bc1-4ce572d070d7.png)
![chrome_rfzgEZVTRg](https://user-images.githubusercontent.com/29508011/226755330-52b5cdbd-d265-45ee-a9ac-631f538fce9f.png)
![chrome_YBXosGOzn9](https://user-images.githubusercontent.com/29508011/226755339-ea8036e6-3898-4855-aa4c-3c5b018b2a6a.png)
# Tech Stack
•	Front-End: Streamlit

•	Back-End: Streamlit

•	IDE: Jupyter Notebook, Pycharm

# How to run this app
1) Clone this repository

2) Create a virtual environment by using this series of commands:

 ----> pip install virtualenv > virtualenv myenv > myenv\Scripts\activate (for windows)

 ----> pip install virtualenv > virtualenv virtualenv_name > source virtualenv_name/bin/activate (for linux)

3) Copy all files from the cloned repo to newly created virtual environment folder.

4) Install all the packages by using the following command: pip install -r requirements.txt
 
5) Now for the final step. Run the app using this command: streamlit run app.py
