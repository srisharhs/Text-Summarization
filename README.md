# Text-Summarization
# Introduction
The main idea was to implement an automatic text generation system that is capable of extracting key information from selected academic papers. Researchers spend hours of time over papers during the course of their research. This solution would optimise this by providing concise and informative summariers of the papers.

The challenge with summarizing text comes from not having enough labeled training data. Researchers have tackled this issue in a paper called "**A Supervised Approach to Extractive Summarisation of Scientific Papers**" [1]. They suggest a way to mine scientific papers and create initial summaries for training data. They also introduce methods, like scoring sentences based on word overlap, and more advanced ones like Recurrent Neural Networks (RNNs) and Long Short Term Memory (LSTM) units. This paper was the basis for the project.

Recurrent Neural Networks (RNNs) are commonly used in text generation because they handle the sequence of words well. However, they struggle with remembering long-term connections between words. Long Short Term Memory (LSTM) units solve this problem by paying attention to previous words in a sentence. This helps create more natural-sounding summaries that consider the context of words. 

Today, the best methods in Natural Language Processing use Transformers like BERT (by Google) [7] and GPT-2 (by OpenAI). These models improve on LSTM's idea of attention by looking at words before and after a word. Our project doesn't reach the same level as these advanced models, but it shows the difference between extractive and abstractive summarization methods. Using Transformers could be a future step for our work.

So, the project gives a comparison of extractive and abstractive summarization methods. It sets the stage for possible advancements in Natural Language Processing, aiming to contribute to progress in the field.
