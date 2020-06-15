# TextParser

TextParser.ipynb contains functions to extract Face Value and list of Products from a text. 

1. Product - Can be a single value or an array
2. FaceValue - The savings on the offer, generally a number (savings that may occur in words are neglected)

**Procedure:**
1. Import Libraries: pandas, re (regex), nltk and textblob
2. Read Data
3. Define Functions
4. Check performance using test cases

**Exercise 1:** Face Value Parser <br>
a. define function that identifies words with currency symbols and extracts numerical value from it. If there are multipple words with Face Values, then the face value is added. <br>
b. Check the performance of the function with test cases<br>
c. Apply the function on the input data<br>

**Exercise 2:** List of Products<br>
a. define function that extracts nouns from the text. Textblob helps in extracting proper noun and phrases.<br>
b. Apply the function and check the performance on input data<br>

**Conclusion:** Both the functions defined have satisfactory performance with the test cases.<br>