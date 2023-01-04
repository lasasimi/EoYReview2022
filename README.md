# EoYReview2022
Text analysis of my Daily Journaling effort. My attempt to learn programming with Python by analysing my Daily Journaling entries in 2022.<br>
I used Google Form to record my day-to-day and export the Google Sheets using `gspread` to be analysed with Python.<br>
[<a href="https://docs.google.com/forms/d/e/1FAIpQLSfcqRrv4fmuOiMt5WDmWzB7saDUst_Lgri0VJohbMea4iD3LQ/viewform">Google Form copy of the Daily Journaling</a>]

I did manage to write 322 entries and did some analyses:<br>
1. Visualising Daily Rating
2. Word Count of Feelings
3. Cleaning Text from Stopwords (and trying Stemming using Sastrawi)
4. Clustering the days using k-means and Affinity Propagation
5. Word Cloud

**The blogpost that explains more about this is here: <a href="https://lasasimi.com/?p=669&preview=true">2022 End of Year Review with Python</a>**

The libraries that I used:<br>
- for wrangling: `pandas`, `numpy`, `re`<br>
- for visualisation: `seaborn`, `matplotlib`<br>
- for analysis: `sklearn`, `nltk`<br>

Still a newbie on Python, so my codes can be more efficient of course. If you have any thoughts about this effort, how to improve this, or you are just interested in self-knowledge through data, feel free to hmu!

- <a href="https://discordapp.com/users/lasmi#4653">Discord</a> <br>
- email: lasasimi@gmail.com<br>
Thanks!

I benefit mainly from this book titled "Text Analytics with Python: A Practitioner's Guide to Natural Language Processing" by Sarkar (2019) and browse codes from Kaggle and StackOverflow (links are in the Jupyter Notebook). 

Book citation:<br>
```
@Inbook{Sarkar2019,
author="Sarkar, Dipanjan",
title="Text Similarity and Clustering",
bookTitle="Text Analytics with Python: A Practitioner's Guide to Natural Language Processing",
year="2019",
publisher="Apress",
address="Berkeley, CA",
pages="453--517",
abstract="In the previous chapters, we covered several techniques to analyze text and extract interesting insights. We looked at supervised machine learning techniques, which are used to categorize text documents into several assumed categories. Unsupervised techniques like topic models and document summarization were also covered, which involved trying to retrieve key themes and information from large text documents and corpora.",
isbn="978-1-4842-4354-1",
doi="10.1007/978-1-4842-4354-1_7",
url="https://doi.org/10.1007/978-1-4842-4354-1_7"
}
```

