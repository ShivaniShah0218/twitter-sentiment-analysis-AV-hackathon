# twitter-sentiment-analysis-AV-hackathon
The problem statement of the sentiment-analysis project can be found on https://datahack.analyticsvidhya.com/contest/linguipedia-codefest-natural-language-processing-1/
The metric used for checking the performance of the algorithm is f1-score.This notebook is able to get 0.878340180347777 f1-score in the hackathon.
For data-preprocessing, words having length less than 3,words other than alphanumerical and starting with '#' are removed.The twitter handlers @ are removed, and words with pattern "$&@*#" are removed.
Using tf-idf features, the model is trained on the dataset.The model is trained using stratified 5-fold cross validation.The classification algorithms used for training the model are random forest and cgboost.However the XGBOOST gives the better results.
Programming Language: Python3
Libraries used: Numpy
                Pandas
                NLTK
                Matplotlib
                Scikit-learn
                XGBoost
                WordCloud
                
