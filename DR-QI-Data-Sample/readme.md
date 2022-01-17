## DR-QI data sample
In this folder, you find a ~5% sample of the Demographic-Rich Qualitative UPV-Interviews Dataset (DR-QI) presented in the paper:
*At the Intersection of NLP and Sustainable Development: Exploring the Impact of Demographic-Aware Text Representations in Modeling Value on a Corpus of Interviews*.

The data from the two countries (Uganda and India) are presented in separate files. Data entries consist of sentences (`text`) with their annotated UPV labels (`labels`), supported with demographic information about the speaker.

For both countries, demographic data is presented in two ways: 

* `[country]_samples_values.json` : in these files, demographic information is presented as categorical features;
* `[country]_samples_vectors.json` : in these files, demographic information is presented as a binary vector, created by concatenating one-hot encoded versions of the demographic features.

Refer to section 3.3 of the paper for a description of the included demographic features.