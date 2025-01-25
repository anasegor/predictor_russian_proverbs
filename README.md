# The predictor of Russian proverbs
### Point: 
##### Input: description of the "essence" of the proverb
##### Output: a suitable Russian-language proverb

The model performs the task of classifying the description to a more appropriate proverb from its own dataset.The model does not generate new proverbs.

Example:

Input: "Сначала хорошо подумай, а потом делай"

Output: "Семь раз отмерь, один раз отрежь"

### Model: 
Pre-training BERT for task of sequence classification.
### Dataset: 
Own dataset consisting of 100 popular Russian sayings (classes) and 300 descriptions to them (1 description consists of 1 sentence).
