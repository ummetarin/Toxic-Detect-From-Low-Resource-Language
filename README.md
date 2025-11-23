Toxic detect from low resource language(Chittagong) using Rnn,Lstm and Bilstm

In this project, we focus on identifying toxic and harmful comments written in the Chittagonian language, which is a low-resource and underrepresented language. Because Chittagonian lacks large annotated datasets and NLP tools, detecting toxic content becomes a challenging task.

Dataset : "https://docs.google.com/spreadsheets/d/1agOE_LgPa33O6UkWV33lqevrBfzo12Rm/export?format=xlsx"

The dataset used in this project is cyberbullying.xlsx, which contains a total of 5047 samples. Each entry includes two columns: Text, which holds the Bangla comment, and Label, which indicates whether the comment is toxic or non-toxic.

Used Model : RNN,LSTM,BI-LSTM

Best Model : The BiLSTM model performs better than the other models because it learns the training data more effectively and captures deeper contextual patterns. It also generalizes well on unseen data by reading text in both forward and backward directions, allowing it to understand meaning more accurately. As a result, BiLSTM achieves higher accuracy compared to both RNN and LSTM, making it the best-performing model for toxic text detection in the Chittagonian language.
