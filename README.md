# NEWSPAPER ARTICLE SUMMARIZATION
NewsPaper Article Summarization using Combinational Method and NLP.
## INTRODUCTION
This repository is a demonstration of News Article Summarization that adopts an extractive approach, scoring sentences based on factors like interconnectivity, emotions, and keyphrases and the resulting application explores user-friendly news summarization, focusing on newspaper articles.
## Difference between Abstractive and Extractive approach
Extractive uses original sentences, offering simplicity but occasionally lacks cohesiveness whereas abstractive summarization constructs abstracts, considering semantics, word sense, and grammar.
## COMBINATIONAL METHOD
In our work, it has been observed how a combinational approach can be used to do summarization of newspaper articles. In the summarization approach at first a newspaper article goes through pre-processing as stop-words are removed. After stop-words removal, the sentences are scored in three methods and the scores are combined.
I have focused on interconnecting Three Algorithms :
#### 1) TEXTRANK ALGORITHM 
#### 2) KEYPHRASE EXTRACTION
#### 3) SENTIMENT ANALAYSIS
## WORK FLOW OF THE MODEL
![Screenshot 2024-05-04 133542](https://github.com/SANJAYS07/News-Summarization/assets/126813962/3816efdf-db3e-46bc-abfb-3d77d0b193b1)
## PRE-REQ
1. Install Python 3
2. Install Flask

## HOW TO RUN
1. Run app.py file (website)
2. Run combined.py for console based output.
3. paste your news article data in the input field.
4. Summarized output will be geberated which will be 60% of the original data size.
   
## SCREENSHOTS 

![Screenshot 2024-05-04 134555](https://github.com/SANJAYS07/News-Summarization/assets/126813962/af266b89-790d-47b8-9908-84af3fec6508)

## RESULTS AND ACCURACY

##### Textrank Algorithm   : 75.53
##### Keyphrase Extraction : 63.77
##### Sentiment Analysis   : 61.84
### COMBINATIONAL METHOD    : 87.18

## RESEARCH PAPER REFERENCE 

Newspaper Article Summarization using Combinational Method
Md. Siam Ansary
Department of Computer Science and Engineering
Ahsanullah University of Science and Technology
Dhaka, Bangladesh
siamansary.aust@gmail.com, siamansary.cse@aust.edu






