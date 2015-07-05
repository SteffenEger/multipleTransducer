# transduce from multiple input strings

## Requirements

* CRF++, http://taku910.github.io/crfpp/

* multiply aligned input strings. A multiple many-to-many aligner can be found here: https://github.com/SteffenEger/multipleMany2ManyAligner

## Running

e.g.

	./run.sh 4 sampleData/sampleAligned.train sampleData/sampleAligned.test

Modify all the local paths etc. in:

decodeMany.py  

and

makeAlignmentsForCrfMultiple.py


The output will be in a file **transduced.dat**

## REFERENCES

If you use this, please cite the following papers:

Eger, Steffen Multiple Many-To-Many Sequence Alignment For Combining String-Valued Variables: A G2P Experiment In: ACL, Association for Computational Linguistics, 2015. Accepted

Eger, Steffen Improving G2P from Wiktionary and other (web) resources. Interspeech 2015. Accepted.

Have fun! Steffen Eger, 07/05/2015

steffen.eger@yahoo.com