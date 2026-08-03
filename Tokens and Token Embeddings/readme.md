Tokenization
Tokenization is an essential process in Natural Language Processing (NLP) that involves breaking down a larger stream of text into smaller textual units, called tokens, which can be in various forms. These tokens can range from individual characters to full words or phrases, depending on the level of decomposition required. Tokenization is performed to enhance the model interpretability and ease in processing.

Features of Tokenization
Breaks large textual data into significantly smaller chunks
Tokens can be of various forms: Sentences, Words, Sub-words, or Characters
Can facilitate various NLP tasks like Summarization, Translation, etc.
Enhances Model Interpretability
Eases the processing by machines

Types of Tokenization
Word Tokenization: Text is divided into individual words.
Character Tokenization: The textual data is split and converted to a sequence of individual characters.
Sub-word Tokenization: This strikes a balance between word and character tokenization by breaking down text into units that are larger than a single character but smaller than a full word.
Sentence Tokenization: Makes a division of paragraphs or large set of sentences into separated sentences as tokens.
N-gram Tokenization: It splits words into fixed-sized chunks (size = n) of data.

Techniques used in Tokenization
Whitespace Tokenization: This method splits text based on the position of spaces. It doesn't handle some different cases like compound words.
Statistical Tokenization: This method of tokenization uses statistical properties in text. These include frequency count of words and probability of co-occurrence.
Transformer-based Tokenization: This method combines sub-words by pre-training vocabulary and also maintain consistency.
Rule-based Tokenization: This approach uses manually defined if-else conditions or rules that are used to handle or tokenize regular expressions, punctuations, etc.
Byte-Pair Encoding: This is a sub-word tokenization algorithm. It iteratively merges most frequent pairs of bytes or characters.

Embedding
Word Embedding is an approach for representing words and documents in the form of a numerical array. These can also be represented as a Word Vector, which is a numeric vector input that represents a word in a lower-dimensional space and can be plotted to visualize the representation. It allows words with similar meanings to have a similar representation. The metrics of similarity used in usually Cosine Similarity.

Features of Word Embedding
Approach used to extract features from textual data. Almost all modern NLP applications start with an embedding layer
To represent or visualize any underlying patterns of usage in the corpus
Inter-word semantics must be captured, extracts inference from the data and preserves syntactical and semantic information
Aims to reduce dimensionality
Faster to train than hand build models

