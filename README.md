# Machine-Translation
Translation of sentences in one lauguage to another language.

This is an implementation of sequence to sequence modeling using RNN( with GRU units) in PyTorch.

Architecture of the Model:
Input -> RNN Encoder -> context Vector -> RNN Decoder -> Output

Input to the RNN Encoder are the word embedding vectors of each of the word in the sentence.
RNN Encoder generates the context vector which is given as a input to the RNN decoder.
Here RNN decoder uses attention mechanism to achieve better accuracy.

For Training Data use http://www.manythings.org/anki/ .

