# Latent-Dirichlet


NLP Project Round-1
● Github Link: https://github.com/mayank-gupta16/Latent-Dirichlet


● Team Name: Latent Dirichlet
● Members:
   1. Saransh Mittal(20UCS174)
   2. Aagam Jain(20UCS001)
   3. Mayank Gupta(20UCS113)
   4. Mihir Chaturvedi(20UCS117)



Task:
1.	Import the text, let’s call it as T1
2.	Perform simple text pre-processing steps
3.	Tokenise the text T1
4.	Analyse the frequency distribution of tokens in T1.
5.	Create a Word Cloud of T1 
6.	Remove the stop words from T1 and then again create a word cloud
7.	Evaluate the relationship between the word length and frequency for T1
8.	Do PoS Tagging for T1 using anyone of the four tag sets studied in the class and get the distribution of various tags

Library Used
NLTK - Used for tokenizing, lemmatization and removing stopwords.
Language Word Cloud - Used to create word clouds from tokenized data.
Matplotlib- Used to Visualize our text data
Seaborn -Used to Visualize our text data
Numpy- Used for working with arrays.
Typing-To perform evaluation of the Algorithm in Entity Recognition

IMPORT THE TEXT T1
 

TEXT PREPROCESSING STEPS
●	Here we have used word_tokenize of nltk library for splitting the text into words.
●	Then we have converted the upper case tokens to lower case tokens .
●	Then we removed the punctuations and digits.
●	Then we also have removed the remaining tokens  which are not alphabetical.
●	Then we  exclude stop words for which we have used nltk.corpus
Frequency Distribution Including stopwords
 
 

Word Cloud Including stopwords
 
 

Frequency Distribution excluding stopwords
 
 


Word Cloud Exluding stopwords
 
 

Inferences:
●	Words like ‘of’, ‘a’ and ‘the’ are the most frequently used words in T1
●	Words like ‘of’, ‘and’, ‘a’, and ‘the’ are frequently used words in T2
●	These words do not contribute to the meaning of the sentence and are mostly useless for us
These words are known as ‘stopwords’, and we need to get rid of them
On excluding stop words, we get a meaningful word cloud as stop words mostly have higher frequency due to which our result might get affected. Now most of the terms that are of no meaning to us have been removed. We have gotten rid of ‘stopwords’ and can draw meaningful conclusions from the data.
Relation between word length and frequency for Text
Including Stopwords:
 
 
Excluding StopWords:
 
 
Inferences:
●	The number of words of length 1  has significantly increased after removing stopwords as now it will also count varialbles like ‘x’ in it.
●	There is a general trend that the highest number of words lies in the length range 3-6.
●	We can infer that this is due to removing stop words like ‘a’, ‘the’, ‘of’ and ‘and’, which were the highest occurring words before removal.
●	POS TAGGING
●	Now the main task is to give each of the tokens their tags. We have used
●	‘averaged_perceptron_tagger’ for POS tagging of the tickets. We have downloaded the same from nltk.
 
 
Frequency Distribution of Tags:

 
 
Inferences
From the above results we infer that the highest occurring tag is ‘NN’, and ‘Determinant’ Tags are on the lower frequency side. This is largely due to the removal of stopwords before POS Tagging.
Conclusion:
We have learnt how to perform Text Preprocessing, Tokenization on Text Data and how to Create word clouds. We have solved all the Problems given to us in NLP Project Round 1 with the use of Plots and Visualisations and learnt to draw meaningful inferences from it.







