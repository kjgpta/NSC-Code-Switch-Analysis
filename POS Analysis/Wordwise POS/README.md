# Wordwise Part-of-Speech Analysis
Looping through every word of a sentence and detect its POS also the language of this word. Now, based on the language and POS of the word we gather stats. 

**Required Libraries**
1. [h5py](https://docs.h5py.org/en/stable/build.html)
2. [typing-extensions](https://pypi.org/project/typing-extensions/)
3. [wheel](https://pypi.org/project/wheel)
4. [imgaug](https://pypi.org/project/imgaug/)==0.2.5
5. [malaya](https://pypi.org/project/malaya/)==4.9.0
6. [tensorflow](https://www.tensorflow.org/install)==2.9.0
7. [tensorflow_addons](https://pypi.org/project/tensorflow-addons/)
8. [Pandas](https://pandas.pydata.org/docs/getting_started/install.html)

## Steps for Analysis 

### Adding Language Tag
First step is to modify our text in such a way to add language tags like `<english>`, `<malay>`, `<other_language>`. Our text had the `<malay>` tag already but it didn't have `<english>` and `<other_language>` tag. 

For example:\
    *Original Sentence:* like I don't get some people `<malay>`punya`</malay>` mindset `<malay>`macam`</malay>`\
    *Modified Sentence:* `<english>`like I don't get some people`</english>` `<malay>`punya`</malay>` `<english>`mindset`</english>` `<malay>`macam`</malay>`

"Adding_Language_Tag.ipynb" adds Language tags to code-switched data

### Generating POS Stats
Finally, we will get wordwise stats by looping through every word and keeping its tag and language information with us and will finally get "POS_results.xlsx".

"Wordwise_POS_Analysis.ipynb" generates wordwise POS stats.

**Those results can be found in "POS Analysis Results.xlsx"** 