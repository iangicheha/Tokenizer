# Tokenizer
BPE Tokenizer from Scratch
A hands-on implementation of the Byte Pair Encoding (BPE) algorithm used in modern LLMs like GPT-2 and GPT-4.
This notebook walks through building a tokenizer from the ground up — starting from raw Unicode text, encoding it as UTF-8 bytes, and iteratively merging the most frequent byte pairs to build a compact vocabulary. It also covers the full encode/decode pipeline, regex-based forced splits (as used in the GPT series), special tokens, and a side-by-side comparison with OpenAI's tiktoken library.
Topics covered: Unicode & UTF-8 · Byte Pair Encoding · Vocabulary building · Encode/Decode · Regex pre-tokenization · GPT-2 vocab & merges · Special tokens (<|endoftext|>)

