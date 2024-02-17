# MA331-Programming-and-Text-Analytics-with-R

#Section 1: Introduction
This part provides a brief introduction to the text analytics methods used in the analysis. It mentions the importance of text analytics in extracting insights from unstructured text data and lists some of the techniques like sentiment analysis, subject modeling, etc.

#Section 2: Methods
In this section, the methods used for text analysis are outlined:

Tidying and Tokenization: It uses the unnest_tokens() function from the tidytext package to tokenize and tidy the ted_talks data into single words.

Stopwords Removal: It eliminates common English stopwords from the tokenized data.

Identification of Speaker-specific Stopwords: It identifies stopwords specific to each speaker.

Visualization of Stopwords: It creates visual representations of stopwords using data visualization techniques.

Visualization for Speakers Separately: It visualizes stopwords for each speaker separately.

Comparison of Speaker Words: It compares the words used by different speakers through data visualization.

#Section 3: Results
This part includes the R code that extracts information about specific speakers ("Sugata Mitra" and "Mariano Sigman") from the 'ted_talks' dataset and then displays the best phrases used by them visually.

#Section 4: Plotting Speaker Words
This section plots the best phrases used by each speaker ("Sugata Mitra" and "Mariano Sigman") visually.

#Section 5: Common Words Plotting between Two Speakers
It visualizes common words between two speakers ("Sugata Mitra" and "Mariano Sigman").

#Section 6: Positive and Negative Words Split
This part involves sentiment analysis by evaluating the sentiment of words using the NRC lexicon.

#Section 7: Sentimental Analysis Plotting
This section plots sentiment analysis results, including log odds ratio and sentiment polarity.
