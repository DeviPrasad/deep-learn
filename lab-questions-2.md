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

Design proper classes, properties, and tests in Python.

# Question 2

Implement Layer Normalization in PyTorch without using nn.LayerNorm.

Requirements:

Accept input tensor of shape (batch_size, seq_len, d_model)
Compute:
  - mean,
  - variance,
  - normalized output.

