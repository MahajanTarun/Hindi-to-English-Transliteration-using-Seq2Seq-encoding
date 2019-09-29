"# Hindi-to-English-Transliteration-using-Seq2Seq-encoding" 


Neural machine translation with Attention mechanism.

We will transliterate Hindi text into English using Sequence to Sequence model.


To learn more about seq2seq model to implement encoder-decoder with attention, you can refer to this tutoril : https://github.com/tensorflow/nmt


To explain in shor:

Attention is a mechanism combined in the RNN (Recursive Neural Network)
allowing it to focus on certain parts of the input sequence when predicting a certain part of output sequence, enabling easier learning and of higher quality.

It improves performance of RNN networks.

The existing problem with RNN network architecture is that the decoder needs to represent the entire input sentence as a single vector. This can cause information loss. Moreover, the decoder need to decipher the passed information from this single vector which is a complex task in itself.

https://www.tensorflow.org/images/seq2seq/attention_mechanism.jpg

"A potential issue with this encoder–decoder approach is that a neural network needs to be able to compress all the necessary information of a source sentence into a fixed-length vector. This may make it difficult for the neural network to cope with long sentences, especially those that are longer than the sentences in the training corpus."


"Using Attention mechanism, the context vector enables the decoder to focus on certain parts of the input when predicting its output."



For deeper understanding of Attention mechanism, you can visit : https://medium.com/datadriveninvestor/attention-in-rnns-321fbcd64f05
