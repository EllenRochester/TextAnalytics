# TextAnalytics

<h2>Summary </h2>
- Predicted doctor’s knowledge ratings on 20K test data using BERT model trained by 80K doctor review, achieving a 92.7% out-sample accuracy; enhanced decision-making regarding medical training needs.

<br />
<br />
- Developed and implemented a data preprocessing pipeline that removed punctuations, numbers, stop words, and white spaces, optimizing the data quality for analysis and improving model performance.
<br />

<h2>Description</h2>
This project involved predicting doctors' knowledge ratings using 80K patient reviews and various machine learning models.
<br />
<br />
Initially, I preprocessed the text for Natural Language Processing (NLP), including tasks like lowercasing, removing punctuation and numbers, normalizing whitespace, and eliminating stopwords. I then tokenized the text, filtered out stopwords, and prepared it for modeling.
<br />
<br />
Data was organized into batches of 32 to optimize training efficiency and divided into training and validation sets. Using TensorFlow Keras' TextVectorization layer, I vectorized the text data for effective deep learning model processing. 
<br />
<br />
I developed an RNN model using a bidirectional GRU and then refined a BERT Transformer model, achieving 91.22% accuracy through parameter adjustments. 
<br />
<br />
Finally, the BERT model was tested on 20K data, achieving a 92.7% accuracy rate and ranking 20th out of 244 participants.



<h2>Languages and Tools Used</h2>

- <b>Python</b>
- <b>TensorFlow, Scikit-learn, Pandas, NumPy, Seaborn</b>
- <b>RNN, Transformer, BERT</b>
