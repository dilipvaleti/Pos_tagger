# Simple English part-of-speech tagger

In corpus linguistics, part-of-speech tagging (POS tagging or POST), also called grammatical tagging or word-category disambiguation, is the process of marking up a word in a text (corpus) as corresponding to a particular part of speech, based on both its definition and its context—i.e., its relationship with adjacent and related words in a phrase, sentence, or paragraph. A simplified form of this is commonly taught to school-age children, in the identification of words as nouns, verbs, adjectives, adverbs, etc. [Wikipedia]

Written in Python 3. Dependencies: `scipy`, `numpy`, `nltk`.   
_NB. all of the above dependencies are not crucial, but still used in code - they will be removed later._  


    
### Interactive sentence tagger
```
python postag-interactive.py
```

### Awesome statistics
```
python correctness.py data/Brown_tagged_dev.txt output/Brown_tagged_dev.txt
```
### An auto testing using wiki module. 
```
python get-random-wikipedia-sentence.py <Optional sentences numerical value>
#heredefault sentence number is 5, if you want wwe can give user defined value
```
### Example

    Sentence > Hello, part-of-speech tagger! NLP is an exciting field of applicable science!
    Tagged : Hello/PRT ,/. part-of-speech/NOUN tagger/NOUN !/. NLP/NOUN is/VERB an/DET exciting/ADJ field/NOUN of/ADP applicable/ADJ science/NOUN !/.



Regards,  
Dilip.
