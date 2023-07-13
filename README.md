# text-summarizer
Automatic Extractive Text Summarization using NLTK: A Python-based implementation that condenses text documents by extracting key sentences based on the weighted frequency of occurrence. The purpose of the summarizer is to condense a given text document into a shorter summary by extracting the most important sentences from the original text. The summarization process is achieved through the following steps:

1. Sentence Tokenization: The text document is divided into individual sentences using NLTK's sentence tokenizer.

2. Weighted Frequency of Occurrence: The frequency of each word in the document is calculated, giving higher weight to words that occur more frequently. This step helps identify key terms in the text.

3. Sentence Scores: Each sentence is assigned a score based on the sum of the weighted frequencies of the words it contains. Sentences with higher scores are considered more important.

4. Summary Generation: Finally, the sentences with the highest scores are selected to form the summary. The selected sentences are concatenated to produce a condensed version of the original text.
