# Question 1
Your mathematics teacher watches your digit-recognition neural network demo and remains unconvinced. 

He says: "I've seen your neural network. It's just matrix multiplication and a threshold — 
any student can do that. **What exactly makes your network deep and why does that depth matter at all?**"

Your job is to answer him — not with words, but with code and evidence.

(A) Implement a single-layer classifier (784 → 10, no hidden layers) on MNIST and train it for 10 epochs. 
    Record the test accuracy and confusion matrix. Identify the two digit pairs it confuses most, and state a hypothesis for why a linear model struggles to separate them.

(B) Run three experiments with architectures M1 (784 → 10), M2 (784 → 64 → 10), and M3 (784 → 64 → 64 → 10). Plot test
    accuracy versus epoch for all three on the same axes. Comment on the accuracy jump from M1 to M2 versus the smaller gain from M2 to M3,
    and explain what the hidden layer in M2 is doing to the input space.


# Question 2

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
