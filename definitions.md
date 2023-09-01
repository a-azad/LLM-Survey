# Multi-task, Curriculum and Meta Learning 

| Model | Brief Description | Pros | Cons | Major Influential Publication |
| --- | --- | --- | --- | --- |
| Multi-Task Learning | Trains a single model to perform multiple related tasks simultaneously, by sharing learned representations across tasks. | Improves performance on related tasks by leveraging shared knowledge. Reduces the need for multiple separate models. | May require more complex architectures or training procedures. Can be sensitive to task relatedness. | "Multitask learning." by Caruana (1997), "A Comprehensive Survey on Multi-Task Learning" by Zhang et al. (2017) |
| Curriculum Learning | Presents training data to the model in a specific order to facilitate learning. Starts with easy examples and gradually increases difficulty. | Can help overcome problems with imbalanced or noisy data. Can speed up training by focusing on the most informative examples. | Requires a well-defined curriculum, which may not always be possible. Can be computationally expensive. | "Curriculum Learning" by Bengio et al. (2009) |
| Meta-Learning | Trains a model to learn how to learn, by adapting quickly to new tasks with limited data and experience. | Can improve generalization and adaptation to new tasks or domains. Can reduce the need for large amounts of labeled data. | Requires additional training data for meta-learning. Can be sensitive to the choice of meta-learning algorithm or architecture. | "Meta-Learning for Few-Shot Learning" by Vinyals et al. (2016) |


# Byte Pair Encoding (BPE)
LLMs adapt byte pair encoding (BPE) (Gage,1994), a compression algorithm, to the task of word segmentation. BPE allows for the representation of an open vocabulary through a fixed-size vocabulary of variable-length character sequences, making it a very suit-able word segmentation strategy for neural network models.

# Rotary Position Embedding (RoPE)
The basic idea behind rotary position encoding is to represent the position information as a continuous angle, which is then encoded as a sine and cosine wave. This angle is updated at each layer of the network, using a fixed rotation matrix that is pre-computed for each position in the sequence.
The rotation matrix is based on the concept of unitary matrices, which are matrices with complex entries that preserve the length of the vectors they operate on. This means that the rotation matrix can be represented as a product of two unitary matrices, one for the sine component and one for the cosine component.
The main advantage of rotary position encoding is that it allows the model to learn the "relative positions" of the input tokens or sequences in a continuous and differentiable way, which can improve the model's ability to generalize to unseen data and improve its performance on complex tasks.

# Attention with Linear Biases (ALiBi)
A simpler and more efficient position method, Attention with Linear Biases (ALiBi). ALiBi does not add positional embeddings to word embeddings; instead, it biases query-key attention scores with a penalty that is proportional to their distance. 

# Fine-tuned LAnguage Net (FLAN)
This involves fine-tuning a model not to solve a specific task, but to make it more amenable to solving NLP tasks in general. We use instruction tuning to train a model, which we call Fine-tuned LAnguage Net (FLAN). Because the instruction tuning phase of FLAN only takes a small number of updates compared to the large amount of computation involved in pre-training the model, it's the metaphorical dessert to the main course of pretraining. This enables FLAN models to perform various unseen tasks.

