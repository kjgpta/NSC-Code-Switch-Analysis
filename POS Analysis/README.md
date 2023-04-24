# Part-of-Speech Analysis

One of the oldest tools avaiable to us to deal with any language is its part-of-speech. These gives a great deal of information about any sentence and its structure. 

Our aim is to obtain information about structure of a sentence, we use this to generate stats and get a detailed information about structure of the code-switched sentence.

There are two kinds of part-of-speech analysis:
## Word-wise POS Analysis
It is the most common part-of-speech analysis used in many tasks. 

In this information about the POS of each word is taken into account and we gather how many times a particular part-of-speech used in english and malay

## Pair-wise POS Analysis
Since, we have to do analysis for code-switched sentences, it becomes highly important that code-switching points are also taken into consideration.

To do so, we calculate stats, detecting code-switching points based on part-of-speech. For example, if Left word is NOUN and right word is VERB, then this kind of analysis could be used for further analysis and applications.

