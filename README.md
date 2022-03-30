# Sentiment_Analysis
This is a **NLP** Project. Goal of this project was to come up with a tool that gives a brief insight into how people on social media platform are reacting to a real-life event. 
This project uses **sentiment analysis** to classify text into two categories on the basis of overall sentiment which are positive and negative. 

1. ## Data collection for training and testing: 
- For training and testing relevant machine learning and deep learning models, a [labelled dataset](https://www.kaggle.com/kazanova/sentiment140) was used. 
- For analytics, data was collected from Twitter using **Twin** API.
- The data collected was converted into **word-embedding vectors** using [Stanford's GloVe](https://nlp.stanford.edu/projects/glove/) pre-trained embeddings.
- Twint has a feature of geolocation but for more accurate results coordinates of districts of each state of india were entered to get desired tweets from across the country.
2. ## Training Models:
- For **sentiment based classification** Machine learning models and RNNs were trained. The results are available in [models comparison.ipynb](https://github.com/utkarshret/Sentiment_Analysis/blob/main/models%20comparison.ipynb)
- **Accuracy** was the only metric used to determine how a model performed.
3. ## Compilation of data:
- The model which gave the **best accuracy** was chosen for future classification.
- All the extracted tweets along with their sentiment and other relevant information were compiled together and published to **Google Sheets** via the **Sheets API**.
- An instance of this whole process can be viewed in [jupyter_google_sheets.ipynb](https://github.com/utkarshret/Sentiment_Analysis/blob/main/jupyter_google_sheets.ipynb).
4. ## Analytics
- A **PowerBI dashboard** was made to display relevant analytics. An instance of dashboard can be found in [sentiment_analysis_tool.pbix](https://github.com/utkarshret/Sentiment_Analysis/blob/main/sentiment_analysis_tool.pbix).


