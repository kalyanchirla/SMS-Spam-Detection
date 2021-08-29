# SMS-Spam-Detection

### Description

Now a days, we receive a lot of messages out of which many are likely to be spam. Detecting whether a message is spam or not is one of major applications of Machine Learning. 

We can identify a spam message by seeing the words in the message. Spam message usually have words such as 'cash', 'prize', 'lucky', 'free', 'win', 'won' to capture your attention towards the message. The objective of this project is identify whether a message is spam (or) not.

This is a binary classification problem to identify whether a message is spam(1) or not-spam(0)

### Software and Libraries

This project uses Python and some of its libraries for execution. You will also need to have software installed to run and execute a [Jupyter Notebook](http://jupyter.org/index.html).

It is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the required packages included with it.

### Getting Started

Using the terminal, navigate to the project directory and run:

`jupyter notebook spam-detection.ipynb`

This will open the project code in jupyter notebook in your browser

### Data

The dataset is downloaded from: [Kaggle](https://www.kaggle.com/uciml/sms-spam-collection-dataset)

The dataset contains one message per line. Each line is composed by two columns: v1 contains the label (ham or spam). 'ham' indicates that the message is not spam. v2 contains the message text.
