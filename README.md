# Code for the ACL Rolling Review submission - ''

## Links to models pre-trained on the EManuals Corpus

- Our proposed RoBERTa-based variants

1. [hierarchical network](https://huggingface.co/AnonymousSub/rule_based_roberta_only_classfn_epochs_1_shard_1)
2. [triplet network](https://huggingface.co/AnonymousSub/rule_based_roberta_bert_triplet_epochs_1_shard_1)
3. [triplet + hier. network](https://huggingface.co/AnonymousSub/rule_based_roberta_hier_triplet_epochs_1_shard_1)

- Ablation studies - changing the document encoder of RoBERTa-based variants to 'Paragraph Encoder + 2-layer transformer' 

1. [hierarchical network](https://huggingface.co/AnonymousSub/rule_based_roberta_only_classfn_twostage_epochs_1_shard_1)
2. [triplet network](https://huggingface.co/AnonymousSub/rule_based_roberta_twostagetriplet_epochs_1_shard_1)
3. [triplet + hier. network](https://huggingface.co/AnonymousSub/rule_based_roberta_twostagetriplet_hier_epochs_1_shard_1)

- Our proposed BERT-based variants

1. [hierarchical network](https://huggingface.co/AnonymousSub/rule_based_only_classfn_epochs_1_shard_1)
2. [triplet network](https://huggingface.co/AnonymousSub/rule_based_bert_triplet_epochs_1_shard_1)
3. [triplet + hier. network](https://huggingface.co/AnonymousSub/rule_based_hier_triplet_epochs_1_shard_1)

- Baselines

1. [bert-base-uncased](https://huggingface.co/bert-base-uncased)
2. [roberta-base](https://huggingface.co/roberta-base)
3. [EManuals_BERT](https://huggingface.co/abhi1nandy2/EManuals_BERT)
4. [EManuals_RoBERTa](https://huggingface.co/abhi1nandy2/EManuals_RoBERTa)
5. [DeCLUTR](https://huggingface.co/AnonymousSub/declutr-model)
6. [CLINE](https://huggingface.co/AnonymousSub/cline)
7. [ConSERT](https://huggingface.co/AnonymousSub/unsup-consert-base)
8. [SPECTER](https://huggingface.co/AnonymousSub/specter-bert-model)

> To get the models fine-tuned on the SQuAD 2.0 models, just add `_squad2.0` at the end of a pre-trained model's link (For example, the link to the 'triplet + hier.' RoBERTa-based model obtained after pre-training and fine-tuned on SQuAD 2.0 is https://huggingface.co/AnonymousSub/rule_based_roberta_hier_triplet_epochs_1_shard_1_squad2.0)
