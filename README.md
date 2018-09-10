# ratnaparkhi-preposition-attachment
The preposition attachment dataset constructed from Penn Treebank in Ratnaparkhi 1994.

## Notes
Downloaded from [ftp://ftp.cis.upenn.edu/pub/adwait/PPattachData/]

The `README.txt` file is the original README distributed with the dataset.

## Dataset
This directory contains the data used for the model described in "[A
Maximum Entropy Model for Prepositional Phrase Attachment](http://www.aclweb.org/anthology/H94-1048)" in the 1994
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
