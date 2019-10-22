# Sentence pair classification for parliamentary turn-taking

Contributors:

1. Helder Monteiro

2. Miriam Sanchez Alcon




## Preprocessing scripts (6 points): 
One or more command-line scripts that will process the XML files and generate training and test data files that your training and evaluation scripts will load. It should be possible to vary the train/test split via command-line options.

Our preliminary steps:

Load data

a. Remove Tags

b. Expand Contractions

c. Remove special characters

d. Mark sentence boundaries (speech boundaries)

e. Save into a csv


Process data

c. Text Lemmatization

d. Tokenization

e. Create Bigrams

## Training and evaluation scripts (9 points): 
Implement one method for training a turn-taking classification model that involves a PyTorch-based neural network, such as the ones suggested above. There should a training script and a separate evaluation script.  You can create your own module files to contain code common to both (optional).  The training script should save a model that will be loaded by the evaluation script (and your final model should be saved and submitted, if it is too large to upload to GitHub contact us and we'll find another way).

## Documentation (5 points): 
Documentation of how to run the code in README.md, as well as reasonably detailed discussion about your design decisions (with motivation), the evaluation, and your linguistic error analysis.

Don't forget to document the member contributions.
