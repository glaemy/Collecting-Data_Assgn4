#Taylor Swift Lyrics NLP Through Spacy

<br>
<br>

##**The corpus:**
The corpus here consists of the lyrics of American music artist Taylor Swift organized by album. The lyrics have been extracted from the website Geniuslyrics and the code for the same was obtained from a Github repositary. 
<br>
##**Your target audience and the intended use of the corpus:**
The corpus is used for the processes of tokenization and lemmatization of the lyrics of Taylor Swift's songs. The intended audience for this repositary and corpus are those interested in the NLP of lyrics in general and Taylor Swifts' writings in particular. 
<br>
##**Text selection criteria:**
The albums selected are the initial ones she recorded under her contract with Big Machine Records and her later new albums under her contract with Republic Records. The rerecorded albums with new and alternate lyrics have not been included. 
<br>
##**The data collection process:**
The data has been collected through the code for its collection on Genius derived from another Github repositary doing an analysis on Taylor Swift lyrics. The code has been included in the uploaded annotation code titled Collecting_Data_Assignment_4.ipynb.
<br>
##**Cleaning and/or preprocessing steps:**
The code for the cleaning and preprocessing of the text has been included in the uploaded annotation code titled Collecting_Data_Assignment_4.ipynb. It also included the manual removal of texts from the txt files. 
<br>
##**Annotations:**
SpaCy library has been used to add Doc, Tokens, Lemma's, Part-Of-Speech and Named Entities and their corresponding NE_Words to the songs. The CSV file has been converted into a dataframe.
<br>
##**Format of the files in the Corpus:**
## Columns in the CSV are as follows: 
| Column Name | Description |
| --- | ----------- |
| Album | The album that the song is under |
| File Name | The name of the song |
| Document | the lyrics of the song as plain text |
| Text | The cleaned lyrics without whitespace in lowercase |
| Doc | spaCy processed text document |
| Tokens | The tokenized text of the respective lyrics |
| Lemmas | The lemmatized text of the respective lyrics |
| POS | Part of speech of the tokens in the respective lyrics |
| Named_Entities | The categories of Named Entities in the respective lyrics |
| NE_Words | The actual words of the Named Entities in the respective lyrics |
<br>
The actual text of the lyrics is stored as a txt file while the data description is in a CSV format.   
