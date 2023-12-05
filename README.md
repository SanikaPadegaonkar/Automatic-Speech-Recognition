# Automatic-Speech-Recognition
Assignment 3 of the course EE679: Speech Processing \
Developed a word-level Hidden Markov Model (HMM) for word recognition within a specified command set, employing various techniques: 

1. Implemented energy threshold-based speech end-pointing and pre-emphasis in the dataset preparation phase.
2. Extracted Mel-Frequency Cepstral Coefficients (MFCC) features for words, used as inputs for training individual HMM models.
3. Trained distinct HMM models for each word using the generated MFCC features.
4. Utilized these trained HMMs to assess test utterances, producing likelihood scores for multiple commands and accurately identifying the command via the highest likelihood score.
5. Enhanced the training dataset by introducing diverse noise types into clean utterances, bolstering the model's capacity to handle and accurately process noisy test utterances.
