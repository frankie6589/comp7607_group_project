# comp7607_group_project

# Reading list 
> Please 1) Make sure dataset is public dataset and accessible 2) Remark if code is available
## Frankie
**- ACL 2021 Prefix-Tuning: Optimizing Continuous Prompts for Generation
    - Model: GPT-2, BART
    - Dataset: Yes (total 3)
    - Task: prefix-tuning and fine-tuning on table-to-text generation for increasing efficiency**
- ACL 2021 SimCSE: Simple Contrastive Learning of Sentence Embeddings
    - Model: BERT
    - Dataset: Yes
    - Task: improve performance in classifying ‘entailment’ or ‘contraction’ from previous sentences using supervised/unsupervised SimCSE model
**- ACL 2021 Implicit Representations of Meaning in Neural Language Models
    - Model: BART, T5transformer LM
    - Dataset: Yes (total 2)
    - Task: proving feasibility of Neural Language Models for contextual word representations**
- ACL 2021 Self-Attention Networks Can Process Bounded Hierarchical Languages
    - Model: Dyck(k,D), seems no available package
    - Dataset: random dataset from HuggingFace
    - Task: proving feasibility of self-attention networks for hierarchical languages
## Eugene
- EMNLP 2021 Improving and Simplifying Pattern Exploiting Training
- EMNLP 2021 ExpBERT: Representation Engineering with Natural Language
- NAACL 2021 Low-Complexity Probing via Finding Subnetworks
- NAACL 2021 Reading and Acting while Blindfolded: The Need for Semantics in Text Game Agents
## Stephy
**- ACL 2022 BitFit: Simple Parameter-efficient Fine-tuning for Transformer-based Masked Languagemodels
    - Model: BERT(base), BERT(large), RoBERTa(base) - using Huggingface interface
    - Dataset: GLUE 
    - Task: compare GLUE task performances of the below
        - full fine-tuning
        - BitFit: fine-tuning on bias parameter OR fine-tuning on partial bias parameter
- EMNLP 2021 Generating Datasets with Pretrained Language Models
    - Model: 
        - Dataset generateion:GPT2? 
        - Performance evaluation: S-BERT(base)/ S-RoBERTa(base)
    - Dataset: original dataset is not provided, but dataset generated by DINO provided
    - Task: use DINO to create labeled datasets automatically for fine tuningm and test performance onSTS12-16, STSb, SICK task**
- NAACL 2021 On the Inductive Bias of Masked Language Modeling
    - Model: 
    - Dataset: SST2 (need to label ground truth)
- ACL 2021 Modeling Fine-Grained Entity Types with Box Embeddings
