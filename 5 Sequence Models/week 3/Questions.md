## Questions

**Sequence models & Attention mechanism**

1. Sequence to sequence model. Encoding and decoding. 
2. How the translation is picked? Why using a conditional language model instead of a greedy?
3. Explain beam search algorithm. What beam width means? 
4. How error analysis on beam search is conducted? Give an example.
5. What is Bleu Score? Pros and Cons of it?
6. Attention model intuition. The problem of long sentences. General mechanism of work.
![image](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%203/Machine%20Translation/images/Screenshot%202020-05-19%20at%2008.04.34.png)
7. Explain how attention model works in general. How attention is computed?
![img1](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%203/Machine%20Translation/images/Screenshot%202020-05-19%20at%2008.07.29.png)
![img2](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%203/Machine%20Translation/images/Screenshot%202020-05-19%20at%2008.07.53.png)
8. Speech recognition basics.  How audio to transcript can be implemented?
![img3](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%203/Machine%20Translation/images/Screenshot%202020-05-20%20at%2008.04.14.png)
9. Trigger word detection algorithm.
![img4](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%203/Machine%20Translation/images/Screenshot%202020-05-20%20at%2008.05.24.png)


**More from the quiz**
10. In beam search, if you increase the beam width BB, how speed, memory usage and quality of the solution will change?
11. What will happen, if we will carry out beam search without using sentence normalization?
12. Under the CTC model, identical repeated characters not separated by the “blank” character (_) are collapsed. Under the CTC model, what does the following string collapse to?
__c_oo_o_kk___b_ooooo__oo__kkk 
