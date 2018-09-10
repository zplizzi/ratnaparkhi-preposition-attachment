This directory contains the data used for the model described in "A
Maximum Entropy Model for Prepositional Phrase Attachment" in the 1994
ARPA Human Language Technology Conference.

Description of Files:

training	: training data

devset		: "development" test set, used for debugging and algorithm
		development.

test		: used to report results

bitstrings	: word classes derived from Mutual Information Clustering
		for the Wall St. Journal.


training, devset, and test are in the format:

<source sentence#> V N1 P N2 <attachment>


All files are compressed using the UNIX command "gzip"

To decompress: "gzip -d <filename>"

Remember to download in "binary" mode.
