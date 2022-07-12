*************************************************************************************************************************************
-There are two Datasets in the repository titled "Text Data" and "IITQuestionData".
-You can also find a text document with an array of Stopwords in the english language.
**************************************************************************************************************************************

In the file titled "Data Engineering", the data in Text Data has been remodelled to a Pandas DataFrame.
You can simply run the notebook in order to execute it. Do change the path of the dataset relative to your machine.
The resultant csv file is titled "Dataset.csv".

In the file titled "NLP-Model(Text Data)" You shall find an LSTM model which predicts the given classes.
Standard tensorflow embeddings have been utilized along with stopwords in order to make sense of the text data.
Do change the path of the csv file relative to your machine.

**************************************************************************************************************************************

In the file titled "NLP-Model(IITQuestionDataset" you shall find an LSTM model which predicts the given classes.
Do change the path of the csv file relative to your machine.

**************************************************************************************************************************************

NOTE- CUDNN can't be utilized with recurrent dropouts. Make sure that the recurrent dropout is set to 0 for the LSTM layer.

"model.add(LSTM(100, dropout=0.2, recurrent_dropout=0))"

**************************************************************************************************************************************
