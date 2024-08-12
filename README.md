# Indonesian Election Twitter/X Sentiment Analysis
> Intoduction

SCST601201 Final Project - 2022/2023 \
Group Member: Amanda Abidah, Syazana Alya\
Sentiment Analysis\
Statistics, University of Indonesia

As the 2024 Indonesian presidential election approaches, public have begun to express their opinions on various social media platforms regarding the candidates running for the presidency, including Twitter, now known as X. Our team has decided to analyze public sentiment towards one of the potential presidential candidates, Prabowo Subianto.
Due to the limited free access towards Twitter API, we're using [snscrape](https://github.com/JustAnotherArchivist/snscrape) to collect out Twitter data using the keyword "Prabowo." To evaluate the sentiment score, we use [Lexicon](https://github.com/fajri91/InSet?tab=readme-ov-file) based analysis which support Bahasa with weight ranging of positive and negative word from -5 to +5.

The goal of our project is to extract and alayze public's opinion towards Indonesian Election in 2024.

---
> Data Source

Data scraping form Twitter/X.

---
> Project Outline

1. Data Preprocessing
2. Tokenization
3. Remove Stop Word
4. Stemming
5. Analysis

---
> Instruction on using the code:

  1. The data set is available in this repository file.
  2. Download the "lexicon_positive" and "lexicon_negative" which contain the sentiment key words and upload it to the EDAProject_SentimentAnalysis.ipynb
  3. Run the code
