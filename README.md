# Chatbot-using-word2Vec-and-cosine-similarity
A conversational chatbot which can provide information of any query about MIST (Military Institute of science and technology). It consists of a dataset named ‘mist_dataset’ which is an excel sheet having 111 data. This dataset represents the responses that our bot will give depending on the query



**Click here** https://drive.google.com/file/d/1TYpXKKlBxVzuVrYfkqMoBNaGyM-DkYgD/view?usp=sharing to download the model.



                                                            METHODOLOGY
                                        
**Language:** Python


**Backend:** Jupyter notebook, Google Colab


**Frontend:** Tkinter


**Intent Classification:**


Imported all the necessary library at first such as genism, pandas, NumPy, nltk,
random, warnings. Then assigned the ‘mist_dataset.xlsx’ in a data frame. The dataset is
preprocessed in order to transform them into a standard and
normalized format.

**• Data Preprocessing:** We simplified our data as much as we could which in turn gave
our model a helping hand to train easily and faster. There are following steps that
we performed in it:


**• Data Cleaning:** To clean the data we can use several methods. We first
removed every punctuation and special characters (if any) from the data
then we tokenized the sentences into words. After this we lowercase all the
words. Also, we removed stop words. We got the list of stop words in the
corpus module.


**• Lemmatization:** Lemmatization is the process of grouping together the
different inflected forms of a word so they can be analyzed as a single item.
We used it so that if someone writes a word ‘mostly’, classifier can
understand it and give us the best result possible.


**Word2vec:** Word2vec is to group the vectors of similar words together in vector space and it
detects similarities mathematically. We used these models to train our data frame
into reconstruct linguistic contexts of words. The output of the Word2vec is a
vocabulary in which each item has a vector attached to it, which simply detected
relationships between words from our dataset.Check https://medium.com/@adriensieg/text-similarities-da019229c894 for more information.


**• Cosine Similarity:**
We used the cosine similarity to calculate a numeric quantity that denotes the
similarity between the two or more vectors. We computed vector representation
by using word2vec. We used it to find the word in the data frame which matches
the most with the user input & give response to generate a conversation.
The cosine similarity is described mathematically as the division between the dot
product of vectors and the product of the Euclidean norms or magnitude of each
vector.check http://nlp.town/blog/sentence-similarity/ for more information on it.


                                                            
                                                            

