# Samplers

Implementing sampling methods and features from HF-transformers/llama.cpp/kobold/etc into Nano-GPT

Implemented:
 - Top K -> Being able to pick the top K tokens, Set k=1 for greedy, otherwise its multinomial
 - Top P -> Unuseable, need to fix the summation
