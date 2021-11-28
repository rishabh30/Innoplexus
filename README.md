

# Project Title

## Innoplexus Hackathon Sentiment-Analysis (24-28 July 2019)

## Problem Description
Given the text and drug name, the task is to predict the sentiment for texts contained in the test dataset. Given below is an example of text from the dataset:

### Example:
Stelara is still fairly new to Crohn's treatment. This is why you might not get a lot of replies. I've done some research, but most of the "time to work" answers are from Psoriasis boards. For Psoriasis, it seems to be about 4-12 weeks to reach a strong therapeutic level. The good news is, Stelara seems to be getting rave reviews from Crohn's patients. It seems to be the best med to come along since Remicade. I hope you have good success with it. My daughter was diagnosed Feb. 19/07, (13 yrs. old at the time of diagnosis), with Crohn's of the Terminal Illium. Has used Prednisone and Pentasa. Started Imuran (02/09), had an abdominal abscess (12/08). 2cm of Stricture. Started ​Remicade in Feb. 2014, along with 100mgs. of Imuran.

For Stelara the above text is ​positive​ while for Remicade the above text is ​negative​.

## Project structure
├── data\
│   ├──test_tOlRoBf.csv\
│   └── train_F3WbcTw.csv\
├── main.ipynb\
├── submissions\
├── requirements.txt\
└── License

### Prerequisites

- GPU(s) with 16Gb RAM (e.g. Tesla V100)

```bash
pip install -r requirements.txt
```

### Usage

### Approach

#### Summary
 
- Tensorflow
- VocabularyProcessor
- Punctuation removal
- LSTM_CNN Model
- Sentiment Analysis