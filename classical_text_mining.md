1.Choose true statements about text tokens. <br>
A.lemmatization needs more storage than stemmning to work<br>
B.Stemming can be done with heuristic rules.<br>
C.Lemmatization is always better than stemming.<br>
D.A model without stemming/lemmatization can be the best.<br>
<br>
答案：A,B,D<br>
<br>
<br>
2.Imagine you have a texts database. Here are stemming and lemmatization results for some of the words:<br>
-----------------------------------------------------------------------------<br>
Word                          Stem                        Lemma<br>
-----------------------------------------------------------------------------<br>
operate                       oper                       operate<br>
-----------------------------------------------------------------------------<br>
operating                     oper                       operating<br>
-----------------------------------------------------------------------------<br>
operates                      oper                       operates<br>
-----------------------------------------------------------------------------<br>
operation                     oper                       operation<br>
-----------------------------------------------------------------------------<br>
operative                     oper                       operative<br>
-----------------------------------------------------------------------------<br>
operatives                    oper                       operative<br>
-----------------------------------------------------------------------------<br>
operational                   oper                       operational<br>
-----------------------------------------------------------------------------<br>
<br>
Imagine you want to find results in your texts database using the folling queries:<br>
1.operating system(we are looking for articles about OS like Windows or Linux)<br>
2.operates in winter(we are looking for machines that can be operated in winter)<br>
<br>
Before execution of our search we apply either steming or lemmatization to both query<br>
and texts. Compare stemming and lemmatization for a givern query and choose the correct <br>
statements.<br>
<br>
A.Stemming provides higher recall for operates in winter query<br>
B.Stemming provides higher F1-score for operating system query.<br>
C.Lemmatization provides higher precision for operates in winter query.<br>
D.Stemming  provides higher precision for operating system query.<br>
<br>
答案：A,C<br>
<br>
<br>
3.Choose correct statements about bag-of-words (or n-grams features).<br>
A.For bag-of-words features you need an amount of RAM at least proportinal to<br>
N X T,where N is the number of documents, T is the number of unique tokens in the dataset.<br>
B.You get the same vectorization result for any words permutation in your text.<br>
C.Hashing vectorizer (object that does vectorizaiton) needs an amount of RAM.<br>
proportional to vocabulary size to operate.<br>
D.Classical bag-of-words vectorizer(object that does vectorization) needs an.<br>
amount of RAM at least proportional to T,which is the number of unique tokens in<br>
the dataset.<br>
E.We prefer sparse storage formats for bag-of-words features.
<br>
答案：D,E<br>
<br>
<br>

4. Let us consider the following texts:<br>
~good movie<br>
~not a good movie<br>
~did not like<br>
~i like it<br>
~good one<br>
Let us count Term Frequency here as a distribution over tokens in a particular text,<br>
for example for text "good one" we have TF=0.5 for "good" and "one" tokens.<br>
![](./pic/term_frequency.png)
<br>

What is the sum of TF-IDF  values for 1-grams in "good movie" text? Enter a math<br>
 expression as an answer .Here's an example of a valid expression:log(1/2)*0.1.<br>
 <br>
 答案： (0.5 * log(5/3))+(0.5 * log(5/2))  <br>

 5.What models are usable on top of bag-of-words features (for 100000 words)?<br>
 A.Naive Bayes<br>
 B.Logistic Regression<br>
 C.SVM<br>
 D.Decision Tree<br>
 E.Gredient Boosted Trees.<br>

 答案：

