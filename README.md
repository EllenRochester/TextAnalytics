# TextAnalytics

<h2>Summary </h2>
- Predicted doctor’s knowledge ratings on 20K test data using BERT model trained by 80K doctor review, achieving a 91.22% accuracy rate; enhanced decision-making regarding medical training needs.

<br />
<br />
- Developed and implemented a data preprocessing pipeline that removed punctuations, numbers, stop words, and white spaces, optimizing the data quality for analysis and improving model performance.
<br />

<h2>Description</h2>
This project aimed to predict doctors' knowledge ratings using 80K patient reviews and different machine learning models.
<br />
<br />
I began by preprocessing the text data to suit Natural Language Processing (NLP) tasks, including Lowercasing, Punctuation Removal, Number Removal, Whitespace Normalization, and Stopword Removal. The data was then tokenized, stopword-filtered, and recombined into processed strings to ensure optimal readiness for the modeling process.
<br />
<br />
After processing the text and pairing it with labels, the data is batched into sets of 32 to enhance model training efficiency. The dataset is then divided into training and validation sets. Utilizing TensorFlow Keras' TextVectorization layer, the text data is vectorized, preparing it for efficient processing by the deep learning model in subsequent steps.
<br />
<br />



<h2>Languages and Tools Used</h2>

- <b>Python</b>
- <b>TensorFlow, Scikit-learn, Pandas, NumPy, Seaborn</b>
- <b>RNN, Transformer, BERT</b>
