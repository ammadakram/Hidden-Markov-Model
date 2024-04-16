# Hidden-Markov-Model

This repo contains 3 notebooks that all deal with Hidden markov models.
A Hidden Markov Model (HMM) is a statistical model used to describe a system that transitions between a set of hidden states over time, generating observable outcomes.

All the code in these notebooks takes heavy inspiration from SLP 3 book by Dan Jurafsky and James H. Martin.

Notebook A: In this notebook, I will be making a Part of Speech (POS) Tagger using an HMM via Supervised Matrix/Parameter Initialization and Viterbi Decoding. In the context of Part-of-Speech (POS) tagging, HMMs are used to model the sequence of words in a sentence as a sequence of hidden states representing the POS tags. The observable outcomes are the actual words in the sentence.

Notebook B: In this notebook, I will be generating Music (no vocals though) using an HMM via Baum-Welch Training Algorithm. In the context of Music Generation, the states might represent underlying musical concepts (like note pitches or chord types), and observations could be specific notes or chords played at a given time. Hence, generating music involves moving through the states based on transition probabilities and producing musical notes based on the emission probabilities associated with each state. The emission probabilities dictate how likely it is to observe each possible note or chord (observation symbol) when in a given state. 
I have also attatched the music produced by the model in the repo.

Notebook C: Hidden Markov Model (HMM) Based Multi-Step Time Series Forecasting with Covariates. In this notebook, I will be utilizing the HMMLearn library for weather forecasting. It would be stupid to use this model in this day and age when we have state of the art models (transformers) that do a way better job of this. 
