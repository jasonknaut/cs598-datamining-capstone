# cs598-datamining-capstone
Final Project for CS598 DM Capstone

### Product Perception Framework Implementation
Almost all of the product perception framework and corresponding analysis is implemented in the Jupyter Notebook. This includes components: 3.1 Preprocessor, 3.3 Product Attribute Selection, 3.4 Product Attribute Vocabulary, 3.5 Phrase Candidate Generator & Tagger, 3.6 Sentiment Scorer, 3.7 Product Attribute Scorer, and 3.8 Robust Data Preparer.

The Product Phrase Extractor (described in section 3.2 of the paper) was conducted using the ToPMine implementation created by the paper's author (http://elkishk2.web.engr.illinois.edu/). The only file requiring modification was the run.sh file, which is included in the topmin directory of this repo.

### All Generated Topics -- 30 Product-Related Topics

The 30 topics generated by the ToPMine algorithm are stored in the topmine/output_topics directory.

### Prepared Data Sets
The original Amazon Reviews 2018 data sets are available here: https://nijianmo.github.io/amazon/index.html

Since the data sets are large, I stored the processed version of the reviews created by the Jupyter Notebook pipeline at the following URL: https://storage.cloud.google.com/jknaut-cs598-dm-capstone/cleaned_reviews.json


