# youtube-video-GPT-summarizer
A simple Proof of Concept to summarize a youtube video using OpenAI APIs

This script summarizes the youtube video using few sentences. The transcript is properly divided in blocks to not exceed the context dimension of GPT-3.5

Set the Environment Variable OPENAI_API_KEY to your OpenAI API key
Launch the Notebook setting the VIDEO_ID of youtube video of interest

The following parameters modify the behavior of the script:

- max_dim: maximum number of words (similar to tokens) that are considered in the source text.
- max_sentences: maximum number of sentences to use to summarize a page
- temperature: temperature parameter

An interesting course on ChatGPT Prompt Engineering is: https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/
