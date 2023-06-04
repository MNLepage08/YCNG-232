# YCNG-232: Natural Language Processing Fundamentals


## :rocket: Assignments

1. [Token, Stop words, Distribution of Term Frequency, Word Cloud on book selected on web: ](https://github.com/MNLepage08/YCNG-232/blob/main/Week_1_LSI.ipynb)Retrieve a book from the web. Estimate the number of sentences/paragraphs/names (places and people) it contains. Select the ten most frequent words in the text as stop words. Identify potential stop words for documents written in a non-speaking language. Shape distribution with histogram of word frequencies. Visualize the word cloud.<p>
   
2. [TF-IDF distribution, Topic detection with LDA, Detection of stop words with TF-IDF on corpus: ](https://github.com/MNLepage08/YCNG-232/blob/main/Week_2_R.ipynb)Collection of the Jane Austen corpus. Visualization of word length / TF-IDF distribution. Computation of a document/word similarity measure based on Tf-Idf matrix. Topic detection using the LDA method. Topic visualization using word clouds and treemaps. Detection of stop words with the TF-IDF method.<p>
   
3. [Sentiment analysis using lexicons (AFINN, NRC, Bing) on Amazon reviews: ](https://github.com/MNLepage08/YCNG-232/blob/main/Week_3_R.ipynb)Combine 3 lexicons (AFINN, NRC, Bing) to quantify sentiment in one. Collect Amazon reviews of 3 items and calculate the percentage of words without stop words for each lexicon. Quantify sentiments attached to reviews. Visualize the top 10 positive/negative/neutral sentiments of the aggregated lexicon.<p>
   
4. [POS: N-Gram tagger with Sentence breaks, Hidden Markov Model and Hugging Face (Flair) Model: ](https://github.com/MNLepage08/YCNG-232/blob/main/Week_4_P.ipynb) Collect a Jane Austen book. Quantify the precision of n-gram tagger for n > 3 with confusion matrix (with & without sentence breaks). Compare the accuracy and the training time of a non-transformer tagger (Hidden Markov Model) to a transformer tagger (Hugging Face - Flair).<p>
   
5. [Change similar words in a sentence, simple plagiarism check and translation program: ](https://github.com/MNLepage08/YCNG-232/blob/main/Week_5_P.ipynb)Write a program that takes a sentence and exchanges each word with another having a similar meaning using WordNet. Based on this program, quantify a similarity score (Jaccard and Cosine) for the two input sentences. Use Open Multilingual Wordnet to write a program that takes a sentence as input, along with information about the language in which this sentence is written and the language into which it needs to be translated.<p>
   
6. [Build simple spelling correction model / auto-completion that suggests possible options for the next word: ](https://github.com/MNLepage08/YCNG-232/blob/main/Week_6_P.ipynb) 
   - Collect smart home commands dataset. Preprocess the sentence with tokenize and put all distinct words into a list. For each word in the user-written sentence that is not in the list, compute the Levenshtein distance and replace the word that minimizes the distance. 
   - Collect smart home commands dataset. Preprocess the sentence with tokenize. Create a 3-gram dictionary of words with a PMI score that associates the probability of each word. Write a function that returns the third word of two written words with decreasing score associated. Use NER with Spacy to never suggest names of people or places.
   
   
7. [R: Q1 - Q2 - Q3 - Q8 - Q9](https://github.com/MNLepage08/YCNG-232/blob/main/Week_7_R.ipynb)
   [P: Q4 - Q5 - Q6 - Q7](https://github.com/MNLepage08/YCNG-232/blob/main/Week_7_P.ipynb)<p>
8. [R: Vectorization](https://github.com/MNLepage08/YCNG-232/blob/main/Week_8_R.ipynb)<p>
9. [P: Chatbots](https://github.com/MNLepage08/YCNG-232/blob/main/Week_9_P.ipynb)


## :mortar_board: Courses

| # | Sessions | Concepts |
| ------------- | ------------- | ------------- |
| 1 | Fundamental Concepts  | Token, Tokenization, String, Metadata, Corpus, Stopword, Term-document matrix |
| 2 | Topic Detection | Term-frequency versus inverse-document-frequency matix (tf-idf) & Latent Direchlet Allocation (LDA) |
| 3 | Sentiment Analysis  | Lexicon & Unigram |
| 4 | Tagging | Bigram & n-gram |
| 5 | Word Networks | WordNet, Hyponym, Hypernum, Meronym, Holonym, Antonym |
| 6 | Correction & Prediction | Minimum Edit Distance |
| 7 | Stemming | Stemming, Normalization, Lemmatization |
| 8 | Vectorization | Cosine similarity, PMI, Lemma, Wordform, Polysemous, Word embedding, Skipgram window & probability |
| 9 | Chatbots | Reflexion, Rule-based chatbot, Self-learning chatbot, Bag of words |
| 10 | Speech | Text to speech, Speech to text|

   
## :books: Bibliography
   
| <img width="300" alt="1" src="https://github.com/MNLepage08/MNLepage08/assets/113123425/edf1c98d-1203-4671-a7d0-b36995115569">  | <img width="300" alt="2" src="https://github.com/MNLepage08/MNLepage08/assets/113123425/53f4d59a-fe73-46de-99a5-b018c2671c25"> | <img width="300" alt="3" src="https://github.com/MNLepage08/MNLepage08/assets/113123425/a8a112a5-a8bf-4c11-88ea-67d274d2503d"> | <img width="180" alt="4" src="https://github.com/MNLepage08/MNLepage08/assets/113123425/f660a68b-b0f9-4268-89e4-a60e74992a39"> |
| :---: | :---: | :---: | :---: | 
| [NLP with Python](https://tjzhifei.github.io/resources/NLTK.pdf) | [Text Mining with R](https://www.tidytextmining.com) | [Speech and Language Processing](https://web.stanford.edu/~jurafsky/slp3/) | [Supervised Machine Learning for Text Analysis in R](https://smltar.com) |
