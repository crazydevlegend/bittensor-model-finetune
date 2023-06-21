# Bittensor Model Fine-tuning
Model Fine-tuning script for Bittensor miners using the dataset generated by validators

[example wandb link generated by one of the opentensor team validators](https://wandb.ai/opentensor/opentensor-validator/runs/kltiefxf/overview?workspace=user-const69)

# Overview

- dataset generated by validators: this will be a link to a wandb run where they can pull the pandas DF
- models are used by miners
- miners train model (any model, like a base llama for instance) on the dataset. They use their own compute (i.e. mining machine with GPU capabilities)
- Once trained, the model can be used as the base of a miner on bittensor.

# Models Supports
- [GPT4All](https://github.com/salahawk/bittensor-model-finetune/tree/main/gpt4all)
