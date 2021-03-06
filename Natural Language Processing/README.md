# NLP

[Analyticsvidhya](https://www.analyticsvidhya.com/blog/2017/01/ultimate-guide-to-understand-implement-natural-language-processing-codes-in-python/)

## Introduction to NLP
  - NLP is a branch of data science that consists of systematic processes for analyzing, understanding, and deriving information from  text data
  - Terms and their meanings
    - Tokenization – process of converting a text into tokens
    - Tokens – words or entities present in the text
    - Text object – a sentence or a phrase or a word or an article

## Text Preprocessing
- 3 major steps of cleaning and standardization of text, making it noise-free - 
    - Noise Removal
    - Lexicon Normalization
    - Object Standardization
    <img src = "https://s3-ap-south-1.amazonaws.com/av-blog-media/wp-content/uploads/2017/01/11180616/Image-1.png">
- **Noise removal**
  - Text that is not in context of the data and end output can be termed as noise
  - Examples are language stopwords, URLs, industry specific words, social media specific hashtags  
- **Lexicon Normalization**
  - Lexicon normalization attemots to use the vocabulary dictionary to tranform words into thier root word form
  - Stemming - Deals with removal of suffixes from the words
  - Lemmatization - Considers the grammar and morphology of the word before making transformations
- **Object standardization**
  - Deals with removing/ replacing texts, phrases that are not present in standard vocabulary dictionaries. Eg. - Internet slangs, hashtags, etc.
  
## Text to Features (Feature Engineering on text data)
Techniques that can be used for converting text to features -
- Syntactic Parsing : Deals with arrangement of words in a pattern that shows relationships among the words. Dependency Grammar and Part of Speech tags are the important attributes of text syntactics


  
## Reference
- [Regular expressions](https://www.analyticsvidhya.com/blog/2015/06/regular-expression-python/)
- NLP cheat sheets
  - [1](https://www.cheatography.com/murenei/cheat-sheets/natural-language-processing-with-python-and-nltk/)
- [Nltk github repo](https://github.com/nltk)
- Text mining vs. NLP
- Stanford
  - [Text based tutorials](https://nlp.stanford.edu/IR-book/html/htmledition/)
  - [Video lectures](https://www.youtube.com/watch?v=OQQ-W_63UgQ&list=PL3FW7Lu3i5Jsnh1rnUwq_TcylNr7EkRe6)
    
