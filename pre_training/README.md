# Pre-training

- Files/Folders

1. `taxonomy_hierarchy` - contains files related to hierarchical classification labels
2. `only_classfn_rule_based_shards.py` - code for pre-training the `hier.` model
3. `triplet_net_rule_based_shards.py` - code for pre-training the `triplet` model
4. `heirarchical_classes_triplet_net_rule_based_shards.py` - code for pre-training the `triplet + hier.` model
5. `only_classfn_two_stage_rule_based_shards.py` - code for pre-training the `hier.` model using 'Paragraph Encoder + 2-layer transformer' as document encoder
6. `two_stage_triplet_rule_based_shards.py` - code for pre-training the `triplet` model using 'Paragraph Encoder + 2-layer transformer' as document encoder
7. `heirarchical_classes_two_stage_triplet_rule_based_shards.py` - code for pre-training the `triplet + hier.` model using 'Paragraph Encoder + 2-layer transformer' as document encoder

> In order to pre-train RoBERTa-based variants, assign `model_type = 'roberta'` in the code, and for BERT-based variants, assign `model_type = 'bert'`.

> Link to the sentence embeddings used in the codes (in the form of `.pickle` files) - https://drive.google.com/drive/folders/1phYFoYcheU7Kzs-kfXuy_RRNAd4qaryi?usp=sharing

