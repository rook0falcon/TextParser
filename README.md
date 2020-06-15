# TextParser

TextParser.ipynb contains functions to extract Face Value and list of Products from a text. 

1. Product - Can be a single value or an array
2. FaceValue - The savings on the offer, generally a number (savings that may occur in words are neglected)

Procedure:
1. Import Libraries: pandas, re (regex), nltk and textblob
2. Read Data

Exercise 1: Face Value Parser
a. define function that identifies words with currency symbols and extracts numerical value from it. If there are multipple words with Face Values, then the face value is added.
b. Check the performance of the function with test cases
c. Apply the function on the input data

Exercise 2: List of Products
a. define function that extracts nouns from the text. Textblob helps in extracting proper noun and phrases.
b. Apply the function and check the performance on input data

Conclusion: Both the functions defined have satisfactory performance with the test cases.