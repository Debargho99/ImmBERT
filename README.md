# ImmBERT

The Transformer model of this Notebook is a Transformer model named ImmBERT. ImmBERT is trained as a RoBERTa Transformer with DistilBERT architecture. The dataset was compiled with three books by Immanuel Kant downloaded from the Gutenberg Project.

ImmBERT was pretrained with a small model of 84 million parameters using the same number of layers and heads as DistilBert, i.e., 6 layers, 768 hidden size,and 12 attention heads. ImmBERT is then fine-tuned for a downstream masked Language Modeling task.
