# Wncc-assignment-
Q1) 
<br>
Ans:- The preprocessing steps I used for my model in order are as follows :-
<br>
      1) Converting all words to lower case (in order to cover those cases when some queries contain some word with a capital letter while our model may be trained with same word for lower case so it may not match giving less accuracy also it may cause unnecesarry increase in vocabulory size of the model )
<br>
      2) removing all commas,question marks,exclamation marks,etc (they dont make diffrence in query recognition much )
<br>
      3) tokenization :- converting queries into tokens (separate words)
<br>
      4) lemmatization :- I used lemmatization because i thought it would not make any diffrence in judging the query if it was words with -ing ending or similar something converted to base word (like playing to play) .It will also reduce vocabulory size and increase accuracy of model 
<br>
      

