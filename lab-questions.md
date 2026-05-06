# Question 1

Consider two tokenizers: tiktoken and IndicBERT (https://github.com/AI4Bharat/IndicBERT)

1. Figure out two similarities and/or differences in these two tokenizers.
2. Create a sentence containing more than 12 meaningful words in Kannada language, and tokenize the same using:
    (a) tiktoken
    (b) IndicBERT
3. Print the token IDs, the decoded token strings, and the token count from each. Compute the character-to-token ratio for both.
4. If you are given a Kannada text generation task, how would you use IndicBERT? What would be your first thought?


# Question 2
1. Implement a single-head scaled dot-product attention layer in PyTorch without using nn.MultiheadAttention or any transformer library.
2. Accept query Q, key K, and value V matrices of shape (seq_len, d_model).

