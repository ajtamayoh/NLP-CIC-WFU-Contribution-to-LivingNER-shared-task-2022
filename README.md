# ParTNER: Paragraph Tuning for Named Entity Recognition on Clinical Cases in Spanish using mBERT + Rules

Authors:

Antonio Tamayo (ajtamayo2019@ipn.cic.mx, ajtamayoh@gmail.com)

Diego A. Burgos (burgosda@wfu.edu)

Alexander Gelbulkh (gelbukh@gelbukh.com)

For bugs or questions related to the code, do not hesitate to contact us (Antonio Tamayo: ajtamayoh@gmail.com)

If you use this code please cite our work:

Tamayo, A., Burgos, D., & Gelbukh, A. (2022). ParTNER: Paragraph Tuning for Named Entity Recognition on Clinical Cases in Spanish using mBERT+ Rules. In CEUR Workshop Proceedings (Vol. 3202). CEUR-WS.

## Abstract

Named entity recognition and normalization are crucial tasks for information extraction in the medical field. They have been tackled through different approaches from rule-based systems and classic machine learning methods with feature engineering to the most sophisticated deep learning models, but most of the time for English. In this work, we present a transfer learning approach started from multilingual BERT to face the problem of Spanish NER in clinical cases by applying a paragraph tuning strategy and simple post-processing in the inference phase. Our system achieved an F1 of 0.8499 in the testing dataset of the LivingNER shared task 2022.

### How to use our model

Option 1: [Hugging Face Space](https://huggingface.co/spaces/ajtamayoh/NLP-CIC-WFU_LivingNER)

Option 2: [Hugging Face Model](https://huggingface.co/ajtamayoh/NLP-CIC-WFU_Clinical_Cases_NER_Sents_tokenized_mBERT_cased_fine_tuned)

### How to replicate our experiments

[source code](https://github.com/ajtamayoh/NLP-CIC-WFU-Contribution-to-LivingNER-shared-task-2022/blob/main/Code.ipynb)
