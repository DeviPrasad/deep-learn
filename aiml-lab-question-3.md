# Question 1

Consider two tokenizers: tiktoken and IndicBERT (https://github.com/AI4Bharat/IndicBERT)

1. Figure out two similarities and/or differences in these two tokenizers.

2. Create  a multilingual sentence of at least 15 words containing
   -(a) Kannada
   - English technical words
   - one emoji
   - one number
   Print the token IDs, the decoded token strings, and the token count from each. Compute the character-to-token ratio for both.
   Write tests.

3. Create a Kannada sentence that intentionally “breaks” one tokenizer more than the other.
   - include transliterated Kannada
   - emojis
   - hashtags
   Print the token IDs, the decoded token strings, and the token count from each. Compute the character-to-token ratio for both.
   Write tests.

4. If you are given a Kannada text generation task, how would you use IndicBERT? What would be your first thought?

# Question 2

Assume you are visitng your high school. Your teachers ask you to explain how a neural network (NN) actually works.
You tell them the theory, and enthusiastically claim that you can demonstrate a toy NN that detects digits: 0, 1, 2,...,8, 9.

You set out to implement one such "simple" NN.

And then, after a few minutes of enthusiatic hacking, you realize it is a non-trivial task.

Show how you would set up a NN for this purpose. Make necessary assumptions and use necessary libraries.
Identify where exactly is the "deep learning" in a network located.

