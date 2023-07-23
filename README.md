# ChatGPT_Chemistry_Assistant
ChatGPT Chemistry Assistant

Please check out https://arxiv.org/abs/2306.11296 for more details.

If you find this work helpful to your research, kindly consider citing the following: 

Zheng, Z.;  Zhang, O.;  Borgs, C.;  Chayes, J. T.; Yaghi, O. M., ChatGPT Chemistry Assistant for Text Mining and Prediction of MOF Synthesis. arXiv preprint arXiv:2306.11296 2023. 

Thank you!

**Contents** 

· Text Mining: PDF Text Processing and Analysis with OpenAI's _gpt-3.5-turbo_ API

· MOF Chatbot: a chatbot answers question based on post text mining data

· Predictive Model: A RF classfifier trained on post text mining data



**Features**

_This text mining assistant includes the following main functions:_

· Extraction of text from PDF files and its division into smaller chunks.

· Classfication of text segments.

· Processing and summarization of the extracted text data.

· Conversion of summarized data into a tabular format.

· Calculation of text embeddings using the OpenAI API.

· Selection of top similarity sections and their neighbors in the data.

· Calculation of text token count using the tiktoken library.





_This MOF Synthesis Assistant tool provides the following core functionalities:_

· Extraction of synthesis information and embeddings from a CSV file.

· Calculation of similarity scores.

· Sorting of text segments based on their similarity scores.

· Selection of top similar synthesis conditions from the sorted data.

· Processing of multiple user questions to maintain a conversational context.

· Use of the OpenAI API to generate text embeddings for user's questions based on the selected synthesis conditions.

· Maintenance of a conversation history for better contextually accurate responses in a conversational interface.

· A user-friendly conversational interface for asking questions related to MOF synthesis conditions.

_This machine learning tool includes the following primary functions:_

· Data Preprocessing: Reads, processes, and drops unused data columns from CSV file.

· Feature Selection: Applies RFECV for robust feature selection.

· Data Splitting: Splits data into training and testing sets with various sizes.

· Hyperparameter Tuning: Performs tuning via RandomizedSearchCV for RandomForestClassifier.

· Model Evaluation: Computes several performance metrics for each model configuration.

· Optimal Model Selection: Selects the best performing model based on balanced accuracy.

· Random Splits: Supports multiple random states for data splitting.

· Reporting: Records all performance metrics in an organized format for model comparison.


**Dependencies**

· This project is built on Python and requires the following libraries:


_openai_

_requests_

_PyPDF2_

_pandas_

_tiktoken_


_sklearn_

_numpy_

_mendeleev_



