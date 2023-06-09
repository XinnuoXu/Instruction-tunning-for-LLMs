# Instuction tuning for LLMs

Language models are pretrained to predict the next token at an incredible scale, allowing them to learn general-purpose representations that can be transferred to nearly any language understanding or generation task. 
To enable this transfer, various methods for aligning language models have thus been proposed, primarily focusing on **instruction tuning** over (instruction, intput, output) triplet datasets.
More recently **reinforcement learning from human feedback (RLHF)**, collected over millions of interactions with human annotators, also has been approved to improve the performance of alignment.
This repo is a literature review for instruction tunning for LLMs.

## Existing LLMs

* [LLaMA](https://arxiv.org/abs/2302.13971)
  - Scales: 13B, 65B
  - Licenses: [GNU General Public License v3.0](https://github.com/facebookresearch/llama/blob/main/LICENSE)
* [Chinchilla]
  - Scales: 70B
  - Licenses: 
* [PaLM]
  - Scales: 540B
  - Licenses: 
* [GPT-3]
  - Scales: 175B
  - Licenses: 

## Instruction Tuning
