1.Let's recall how we treated words as one-hot sparse vectors in BOW and dense embeddings in neural networks.<br>
![](./pic/one_hot.png)  <br>
<br>
Choose correct statements below.
<br>
A.For both word representations we can take a weighted sum of vectors <br>
corresponding to tokens of any text to obtain good features for this <br>
text for further usage in linear model. The weight for any token can be <br>
an IDF value for that token. <br>
B.For both word representations we can take a sum of vectors corresponding <br>
to token of any text to obtain good features for this text for further <br>
usage in linear model. <br>
C.Linear model on top of a sum of neural representations can work faster <br>
than on top of BOW.  <br>
D.You can replace word2vec embeddings with an random vectors to get a good <br>
features descriptor as a sum of vectors corresponding to all text tokens. <br>


答案：A，B,C  <br>
<br>
2. Let's recall 1D convolution for words:
![](./pic/word_embedding.png)  <br>
<br>
What is the result of 1D convolution + maximum pooling over time for the <br>
following kernel without padding? <br>
<br>
![](./pic/kernel.png)  <br>
<br>

答案：

<br>

3.Let's recall 1D convolutions for characters. Choose correct statements . <br>
<br>
A.One 1D convolutional layer for spotting character 3-grams is enough for solving a practical task. <br>
B.1D convolutions for characters consume one-hot encoded vectors for characters. <br>
C.1D convolutions work better than BOW for huge datasets.

<br>
答案：B,C