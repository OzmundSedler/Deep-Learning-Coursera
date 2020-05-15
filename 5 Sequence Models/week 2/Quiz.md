## Quiz

**Natural Language Processing & Word Embeddings**

1. **Suppose you learn a word embedding for a vocabulary of 10000 words. Then the embedding vectors should be 10000 dimensional, so as to capture the full range of variation and meaning in those words.**

- False

2. **What is t-SNE?**

- A non-linear dimensionality reduction technique

3. **Suppose you download a pre-trained word embedding which has been trained on a huge corpus of text. You then use this word embedding to train an RNN for a language task of recognizing if someone is happy from a short snippet of text, using a small training set.
Then even if the word “ecstatic” does not appear in your small training set, your RNN might reasonably be expected to recognize “I’m ecstatic” as deserving a label y = 1y=1.**

- True

4. **Which of these equations do you think should hold for a good word embedding? (Check all that apply)**

- e_{boy} - e_{girl} ≈ e_{brother} - e_{sister}
- e_{boy} - e_{brother} ≈ e_{girl} - e_{sister} 

5. **Let EE be an embedding matrix, and let o1234 be a one-hot vector corresponding to word 1234. Then to get the embedding of word 1234, why don’t we call E∗o1234 in Python?**

- It is computationally wasteful.

6. **When learning word embeddings, we create an artificial task of estimating P(target \mid context)P(target∣context). It is okay if we do poorly on this artificial prediction task; the more important by-product of this task is that we learn a useful set of word embeddings.**

- True

7. **In the word2vec algorithm, you estimate P(t \mid c)P(t∣c), where tt is the target word and cc is a context word. How are tt and cc chosen from the training set? Pick the best answer.**

- c and t are chosen to be nearby words.

8. **Suppose you have a 10000 word vocabulary, and are learning 500-dimensional word embeddings. The word2vec model uses the following softmax function:
P(t∣c)=eθTtec∑10000t′=1eθTt′ec
Which of these statements are correct? Check all that apply.**

- θt and ec are both 500 dimensional vectors.
- θt and ec are both trained with an optimization algorithm such as Adam or gradient descent.

9. **Suppose you have a 10000 word vocabulary, and are learning 500-dimensional word embeddings.The GloVe model minimizes this objective:
min∑10,000i=1∑10,000j=1f(Xij)(θTiej+bi+b′j−logXij)2
Which of these statements are correct? Check all that apply.**

- θi and ej hould be initialized to 0 at the beginning of training.
- Xij is the number of times word i appears in the context of word j.
- The weighting function f(.)f(.) must satisfy f(0) = 0f(0)=0.

10. **You have trained word embeddings using a text dataset of m1 words. You are considering using these word embeddings for a language task, for which you have a separate labeled dataset of m2 words. Keeping in mind that using word embeddings is a form of transfer learning, under which of these circumstance would you expect the word embeddings to be helpful?**

- m1 >> m2