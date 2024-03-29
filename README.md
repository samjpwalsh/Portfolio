# Data Science Projects:

## [MSc Dissertation - Exploration by Random Network Distillation in Sparse Reward MiniGrid Environments](https://github.com/samjpwalsh/msc_dissertation)

   - Investigation of Intrinsic Motivation (specifically Random Network Distillation) as a method to encourage exploration for Reinforcement Learning agents
   - A range of RL algorithms were applied including DQN, PPO and RND+PPO
   - Investigations were completed in Minigrid environments (https://minigrid.farama.org/)
   - Exploration was evaluated using both quantitative and qualitative measures
   - A thorough review of state of the art RL literature was undertaken and grounded in RL theory.

## [Deep Learning Image Classification](https://github.com/samjpwalsh/Deep_Learning_Image_Classification)

   - Exploration of image classification using various neural network architectures
   - Data visualisation using principle component analysis
   - Binary classification using support vector machine
   - Binary classification using linear perceptron
   - Comparisons of various multi-layer perceptrons
   - Comparisons of Convolutional Neural Networks
   - CNN visualisation and how it can help in understanding CNN operations
   - Multi-Task Learning

## [Product Review Opinion Mining](https://github.com/samjpwalsh/Product_Review_Opinion_Mining)

   - NLP task to extract product features and assign positive or negative sentiment to those features.
   - Data source is Amazon reviews of various products
   - Spacy's NLP pipeline was used to first pre-process the data then identify nouns and noun phrases (potential features) along with adjectives (likely sentiment bearing)
   - Features pruned using Pointwise Mutual Information (PMI)
   - Sentiment analysed using Naive Bayes classification
   - The final output are product summaries, consisting of the extracted features and aggregate sentiment towards those features
   - The approach taken here was inspired by Hu and Liu, 2004 (https://www.cs.uic.edu/~liub/publications/kdd04-revSummary.pdf)

## [Decision Tree Classification](https://github.com/samjpwalsh/Decision_Tree_Classification)

- Decision tree classifier built from scratch using CART approach
- The algorithm parses a dataset, producing and clearly displaying binary decision tree
- This is tested on two seperate datasets and performance is evaluated using a confusion matrix and k-fold cross validation

## [Car Review Sentiment Analysis](https://github.com/samjpwalsh/Car_Review_Sentiment_Analysis)

- Supervised Learning Classification task to identify positive or negative sentiment in plain text car reviews
- Dataset includes labled reviews but has not been otherwise amended prior to the analysis
- Data is initially pre-processed, stopwords and punctuation removed and words stemmed
- Data is vectorized and sklearn's multinomial Naive Bayes model is trained, using a bag-of-words representation
- Model is extended to bigram and trigrams
- Accuracy is assessed using confusion matrices

## [Naive Bayes Spam Classifier](https://github.com/samjpwalsh/NB_Spam_Classifier)

- Supervised Learning classification task
- Dataset represents a pre-processed set of emails, with the first column representing the binary response variable (either 1 indicating spam, 0 otherwise). The remaining columns represent the presence of a particular word in the email
- Algorithm used for classification is Naive Bayes, using a binary bag-of-words model
- K-fold cross validation used to optimise the smoothing parameter, alpha


# Other AI Related Projects:

## [Genetic Algorithm](https://github.com/samjpwalsh/Genetic_Algorithm)

- Solution to the 8-queens puzzle (https://en.wikipedia.org/wiki/Eight_queens_puzzle) and generalisation to N-queens using a Genetic Algorithm
- Algorithm explores the search space for solutions by simulating evolution by natural selection
- Hyperparameters (mutation rate and population size) are optimised so the time taken to solve the problem is minimised
- Minimal conflicts heuristic inspired by Heris and Oskoei (2014) is also introduced to avoid missing solutions which are close by in the search space, more information can be found here: https://ieeexplore.ieee.org/abstract/document/6802550

## [Sudoku Solver](https://github.com/samjpwalsh/Sudoku_Solver)

- This algorithm takes a 9x9 numpy array as input, if the array is a valid and solvable sudoku puzzle (with zeros in place of blank cells) it returns the solved puzzle, otherwise it returns a 9x9 array of zeros
- The algorithm uses a backtracking depth first search, along with constraint satisfaction to find a valid solution
- A detailed explaination of each part of the algorithm can be found in the detail.md file

## [Enigma Machine Simulator](https://github.com/samjpwalsh/Enigma_Machine_Simulator)

- Simulation of an Enigma Machine used by Nazi Germany during the second world war (https://en.wikipedia.org/wiki/Enigma_machine)
- The code builds an Enigma Machine from scratch in a modular way, with the settings initialised when an instance of the class is created
- This can be used to send encoded messages or decode messages from a physical enigma machine

