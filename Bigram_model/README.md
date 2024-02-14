
# Bigram Character-Level Language Model

### Overview
In this project, I delved into the realm of bigram character-level language models. The journey covered various aspects, starting from the introduction of the model to the training process, sampling, and evaluation using negative log likelihood loss.

### Key Highlights
* **Model Training**: Explored two distinct methods for training the model. The first method involved tallying up the frequencies of all bigrams and normalizing, while the second approach utilized the negative log likelihood loss as a guide to optimize the counts matrix or array. Remarkably, both methods yielded identical results.

* **Training Variability**: Despite achieving the same outcome, the second method, employing a gradient-based framework, emerged as more flexible. The neural network employed in this framework is rudimentary, taking a single previous character and passing it through a linear layer to compute logits.

* **Model Evaluation**: Assessed the model's quality using the negative log likelihood loss. This provided a quantitative measure to gauge the performance of the bigram character-level language model.

* **Model Architecture**: Currently, the neural network is simple, involving a single linear layer. The focus is on a single previous character, and the logits are computed based on this input.
