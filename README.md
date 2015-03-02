Utilities for Character Extraction for SE410
-----------
###Note: The Genderize.io API is free, but limited at 1000 names/day. When developing your system, you may use a small file for testing. 

The Java class NERFromNovel.java extracts characters from a text file and returns a list of Person objects. Each Person object has three attributes: *firstName*, *lastName*, and *gender*.


The class uses the stanford NER library for PERSON recognization and the Genderize.io service for gender classification. 


To use the class, you must download the stanford NER library and jgenderize implementation and put them in approriate build path. Note: jgenderize depends a number of libraries. 


1. [stanford NER library](http://nlp.stanford.edu/software/CRF-NER.shtml)
2. [Genderize.io](https://genderize.io/)
3. [jgenderize implementation](https://github.com/irobson/jgenderize)