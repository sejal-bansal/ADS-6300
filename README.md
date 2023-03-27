## Execution order for drafts

- generate.ipynb - generate reviews
- clean.ipynb - clean the text
- preprocess.ipynb - preprocess the text
- train.ipynb - train and test the model

*_simple - less variety in reviews

*_one - *_simple + four classifiers (one per aspect) instead of the multiclass-multioutput classifier

*_big - reviews with increased size

*_posneg - *_one + reviews with pos/neut/neg instead of ratings

*_stop - *_one + removed stop words (best result)

*_df - *_top + ngrams + df

*_total - *_simple + total rating instead of aspects' ratings

*_w2v - *_one + a pre-trained corpus instead of TF-IDF vectorization