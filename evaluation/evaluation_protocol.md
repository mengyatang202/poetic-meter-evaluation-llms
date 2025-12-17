# Evaluation Protocol

Poetic meter identification is formulated as a multiple-choice task.

For each poem:
- one correct meter label (gold label)
- three distractor meter labels

Models are prompted to select one option.

Accuracy is computed as:
number of correct predictions / total number of poems

The random baseline accuracy is 25%.
