# Tokenization

Prerequisites:
---------------
1. Install the `nltk` library if not already installed by using the following command:
    !pip install nltk

2. Import necessary modules from `nltk`:
    - `word_tokenize` from `nltk.tokenize` for splitting text into words.
    - `FreqDist` from `nltk.probability` for calculating frequency distribution of words.

3. Download the 'punkt' tokenizer models for sentence splitting:
    nltk.download('punkt')

Code Explanation:
------------------
1. `text`: A string variable containing the text to be tokenized.
2. `tokens = word_tokenize(text)`: Tokenizes the input text into individual words (tokens).
3. `print(tokens)`: Prints the list of tokens generated from the input text.
4. `print(len(tokens))`: Prints the total count of tokens in the text.
5. A for loop iterates over each token to compute its frequency:
    - `FreqDist(t)`: Calculates the frequency distribution of each token and prints it.
