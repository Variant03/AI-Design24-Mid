---
library_name: transformers
license: mit
base_model: gpt2
tags:
- generated_from_trainer
model-index:
- name: gpt2-wikitext2
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# gpt2-wikitext2

This model is a fine-tuned version of [gpt2](https://huggingface.co/gpt2) on an unknown dataset.
It achieves the following results on the evaluation set:
- Loss: 5.0230

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 2e-05
- train_batch_size: 8
- eval_batch_size: 8
- seed: 42
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- num_epochs: 3.0

### Training results

| Training Loss | Epoch | Step | Validation Loss |
|:-------------:|:-----:|:----:|:---------------:|
| 5.4451        | 1.0   | 2804 | 5.3846          |
| 5.0583        | 2.0   | 5608 | 5.1090          |
| 4.9032        | 3.0   | 8412 | 5.0230          |


### Framework versions

- Transformers 4.45.0.dev0
- Pytorch 2.4.1+cu124
- Datasets 3.0.0
- Tokenizers 0.19.1
