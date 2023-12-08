> ## A jupyter notebook, analysing all Airbnb reviews in London between 2010-2020, in order to try find the reasons for Airbnb's growth as a company.

- Imported and Preprocessed the data using pandas and NLTK toolkits. Removing stop words, punctuation, and non
english reviews. Allowing for a cleaner set of data.

- Used a topic model, an unsupervised learning technique to obtain the most common ”topics” from each
year of the data. These topics are created from the most semantically similar words used in that year. Two
different topic models were used, NMF and LDA, which have varying results due to different algorithms.

- Tested results of topic models by creating a word count using tokenization. Counted the exact amount of times a
word was used each year and compared them to the topic model results to test accuracy,
- Used python module lexicalrichness to calculate Type Token Ratio of reviews. This was calculated from 2010-2019,
both cumulatively and individually per year. Results were used to argue whether Airbnb’s growth was for social
reasons or not.

- All topic models, word counts, and type token ratios were graphically shown using tools such as PrettyTable and
matplotlib, making the Jupyter Notebook more clear and readable.

[The most up to date data can be found here](http://insideairbnb.com/get-the-data/)
