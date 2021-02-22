# Neural Machine Translation

In the last years translating industry has met with new and great-working auto translating systems. Google,Facebook,Ebay and other big IT companies used a new method instead of phrase-based or syntax-based translation systems: Neural Machine Translation

In Neural Machine Translation systems we use Recurrent Neural Networks and word embeddings. Also we use seq2seq architecture. Seq2seq is an end to end model but has 2 parts: encoder and decoder.

Encoder creates a thought vector using the source text (in this example source text's are English and destination texts are Turkish) and decoder takes thought vector from the inital state of deep GRUs (Gated Recurrent Unit)

This model is word based and trained on a small data, so its not as good as a model that trained on a big dataset. Because of license problems I am not able to share dataset but I will give the link of word embeddings, they're open to  public.

Stanford University Glove Vectors: https://nlp.stanford.edu/projects/glove/
