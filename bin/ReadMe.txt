Sam Hage
Philip Chang
Homework 6

Files: SpamFilter.java, features.txt, ham and spam test emails, enron_words.py (not required for running)
Output file: output.txt

No known errors.

Successful classification: 84-86%
False positive rate: 8-9% 
False negative rate: 6-7%

To improve our performance we used log probabilities and lambda smoothing. We also did our preprocessing in several stages: We wrote a python script to read all the emails and compile lists of the most common words. Then we selected out useful words by hand (i.e. excluding “the”, “a”, etc.), creating features.txt. Our preprocessing method in SpamFilter.java reads from features.txt.