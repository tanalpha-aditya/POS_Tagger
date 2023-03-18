# POS_Tagger

Neural POS Tagging
Designing, implementation and training a neural sequence model (RNN, LSTM, GRU, etc.) of your choice to (tokenize and) tag a given sentence with the correct part-of-speech tags. For example, given the input

Mary had a little lamb
your model should output
Mary    NOUN
had VERB
a   DET
little  ADJ
lamb    NOUN
Note that the part-of-speech tag is separated from each word by a tab \t character.


Dataset
Used the Universal Dependencies dataset, downloadable here. We recommend the
files located at ud-treebanks-v2.11/UD_English-Atis/en_atis-ud-{train,dev,test}.conllu. Use the first, second and fourth columns only (word index, lowercase word, and
POS tag).
The UD dataset does not include punctuation. You may filter the input sentence to remove punctuation before tagging it.
Note that many languages’ data are downloadable from this resource. We expect a model trained on the English data at least, but you are free to train on other languages in addition.
