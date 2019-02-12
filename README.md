# Terms: an experiment in classifying the Terms of Service and Privacy Policies

An exploratory project using Natural Language Processing techniques and Machine Learning to build a tool to help classify Terms of Service and Privacy Policy snippets to better uncover meaning, potentially be made easier to understand, or otherwise improve awareness.

The current solution builds on the ‘Terms of Service; Didn’t Read’ public database of crowdsourced extracts and reviews and achieves an accuracy rate of 75% in predicting unfavourable terms and 67% in predicting one of twenty subject topics, against a baseline of 11%.

Based on this exploration, I’m in the process of building a proof-of-concept front-end to demonstrate the end-user application, before refining the accuracy further through additional data, model tuning and re-evaluation of the classification framework. Stay tuned for updates.

## Repository Contents:

### Classifier

- current jupyter notebook containing outline of project and modelling

### data (folder)

- CSV files of source data (from ToS;DR, scraped, cleaned, some manual review)

### web-app (folder)

- flask / html files for front-end (pending)