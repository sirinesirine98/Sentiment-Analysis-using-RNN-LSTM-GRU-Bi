# Sentiment Analysis using RNN, LSTM, GRU & Bi LSTM
## About
With the rapid development of the Internet, more and more users expressed their views on the Internet. Therefore, the big data of texts are generated on the Internet. Social media is generating a vast amount of sentiment rich data in the form of tweets, status updates, blog posts etc. In the era of big data and deep learning, mining the sentiment tendencies contained in massive texts on the Internet through natural language processing technology has become an important way of public opinion supervision. This analysis has a vast and great applications such as stock price prediction, election result prediction, and so on. In this paper, I have applied a simple and efficient Neural Language Model approach for text classification (Sentiment Analysis) that relies only on unsupervised word representation inputs along with word embedding technique, which has improved the model to capture syntactic and semantic word relationships. This paper shows that applying the RNN, LSTM, GRU, Bidirectional RNN models achieves excellent result on the customer review dataset.


## My Models
I have applied four models for sentiment analysis and trained and tested them over the customer review dataset.
- RNN model that employs embedding layer followed by a simple RNN layer followed by a fully connected layer with dropouts and then by an activation layer. <a href="https://drive.google.com/drive/folders/1YiJOBzJ4urf5zi_-SyYbDhEPZDrukX3w?usp=sharing" target="_blank">Drive Link</a>
- LSTM model that employs embedding layer followed by an LSTM layer followed by a fully connected layer with dropouts and then by an activation layer. <a href="https://drive.google.com/drive/folders/1m2QrCc-sPNcxbHoLX-WajD5VLRt0gadd?usp=sharing" target="_blank">Drive Link</a>
- GRU model that employs embedding layer followed by a GRU layer followed by a fully connected layer with dropouts and then by an activation layer. <a href="https://drive.google.com/drive/folders/13wjft1zqOYC6WdglZ6gGWq-3cvPIqjn5?usp=sharing" target="_blank">Drive Link</a>
- Bidirectional RNN model that employs embedding layer followed by a bidirectional LSTM layer followed by a fully connected layer with dropouts and then by an activation layer. <a href="https://drive.google.com/drive/folders/12mPiXysjQJcH_kcPWML8uAnDJTBBi2ag?usp=sharing" target="_blank">Drive Link</a>


## Results 
- The RNN model achieved an accuracy of 77.85% with a loss score of 0.506 on the testing data.
- The LSTM model achieved an accuracy of 88.94% with a loss score of 0.323 on the testing data.
- The GRU model achieved an accuracy of 84.94% with a loss score of 0.342 on the testing data.
- The bidirectional RNN model achieved an accuracy of 90.57% with a loss score of 0.317 on the testing data.


# Structure and Result #

|<img src="Structure and Result/RNN.png" width="267">|<img src="Structure and Result/LSTM.png" width="267">|<img src="Structure and Result/GRU.png" width="267">|
|:--:|:--:|:--:|
|**RNN Structure**|**LSTM Structure**|**GRU Structure**|


|<img src="Structure and Result/birnn.png" width="267">|<img src="Structure and Result/acc_rnn.png" width="267">|<img src="Structure and Result/acc_lstm.png" width="267">|
|:--:|:--:|:--:|
|**Bi LSTM**|**Accuracy plot of RNN**|**Accuracy plot of LSTM**|

|<img src="Structure and Result/acc_gru.png" width="267">|<img src="Structure and Result/acc_birnn.png" width="267">|<img src="Structure and Result/con_mat_rnn.png" width="267">|
|:--:|:--:|:--:|
|**Accuracy plot of GRU**|**Accuracy plot of Bi LSTM**|**Confusion matrix of RNN**|

|<img src="Structure and Result/con_mat_lstm.png" width="267">|<img src="Structure and Result/con_mat_gru.png" width="267">|<img src="Structure and Result/con_mat_birnn.png" width="267">|
|:--:|:--:|:--:|
|**Confusion matrix of LSTM**|**Confusion matrix of GRU**|**Confusion matrix of Bi LSTM**|

## Tools Used
* [Tensorflow](https://www.tensorflow.org/) : Used as the Deep Learning Library.
* [Keras](https://keras.io/) : For Models.
* [Kaggle](https://www.kaggle.com/) : For Datasets.
* [SK Learn](https://scikit-learn.org/) : For Data Preprocessing & Results.

## Future Possibilities and Extension of this project
- Applying in real time applications like **Election Result Prediction** and **Stock Price Estimation**.
- **Fake News Prediction**


