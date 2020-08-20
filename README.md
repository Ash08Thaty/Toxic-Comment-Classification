# Toxic-Comment-Classification
In this project, I worked on classifying a large set of Wikipedia comments as being either toxic or not (i.e. comments that are disrespectful, rude, or vulgar). The data set I used was taken from the Toxic Comment Classification Challenge on Kaggle. This problem is highly important, given the discussions tech companies and the global community are having on online harassment, content moderation, and inclusivity.

I slightly modified the data set for this project to be a binary classification problem rather than a multi-headed model, as used in the Kaggle challenge, that’s capable of detecting different types of of toxicity like threats, obscenity, insults, and identity-based hate.

I applied word embeddings for text classification, used 1D Convolutions as feature extractors for text in NLP, and performed binary text classification using Deep Learning with Keras. The project workflow is categorized into following tasks: 1: Import Packages 2: Load and Explore the Data 3: Data Preparation — Tokenize and Pad Text Data 4: Prepare Embedding Matrix with Pre-trained GloVe Embeddings 5: Create the Embedding Layer 6: Build the Model 7: Train the Model 8: Model Evaluation - Classify Toxic Comments
