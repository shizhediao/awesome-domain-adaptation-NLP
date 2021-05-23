# awesome-domain-adaptation-NLP
domain adaptation in NLP

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT) 

This repo is a collection of AWESOME things about domain adaptation in NLP, including papers, code, etc. Feel free to star and fork.
Please feel free to pull requests or report issues.

# Contents
- [awsome-domain-adaptation](#awsome-domain-adaptation)
- [Contents](#contents)
- [Papers](#papers)
  - [Survey](#survey)
  - [Theory](#theory)
- [Code Repos](#code-repos)
- [Lectures and Tutorials](#lectures-and-tutorials)
- [Other Resources](#other-resources)

# Papers

## NAACL 2021
* Meta-Learning for Domain Generalization in Semantic Parsing [NAACL 2021] [[__pdf__](https://arxiv.org/pdf/2010.11988.pdf)][[__code__](https://github.com/berlino/tensor2struct-public)]
* UmlsBERT: Clinical Domain Knowledge Augmentation of Contextual Embeddings Using the Unified Medical Language System Metathesaurus [NAACL 2021] [[__pdf__](https://arxiv.org/pdf/2010.10391.pdf)][[__code__](https://github.com/gmichalo/UmlsBERT)]
* DART: Open-Domain Structured Data Record to Text Generation [NAACL 2021] [[__pdf__](https://arxiv.org/pdf/2007.02871.pdf)][[__code__](https://github.com/Yale-LILY/dart)]
* OodGAN: Generative Adversarial Network for Out-of-Domain Data [NAACL 2021 Industry track] [[__pdf__](https://arxiv.org/pdf/2104.02484.pdf)]
* Leaving No Valuable Knowledge Behind: Weak Supervision with Self-training and Domain-specific Rules [NAACL 2021] [[__pdf__](https://www.microsoft.com/en-us/research/uploads/prod/2021/03/SelftrainWS-NAACL2021.pdf)][[__code__](https://github.com/microsoft/ASTRA)]
* QMSum: A New Benchmark for Query-based Multi-domain Meeting Summarization [NAACL 2021] [[__pdf__](https://arxiv.org/pdf/2104.05938.pdf)][[__code__](https://github.com/Yale-LILY/QMSum)]
* UDALM: Unsupervised Domain Adaptation through Language Modeling [NAACL 2021] [[__pdf__](https://arxiv.org/pdf/2104.07078.pdf)][[__code__](https://github.com/ckarouzos/slp_daptmlm)]

## EMNLP 2021
* Wasserstein Distance Regularized Sequence Representation for Text Matching in Asymmetrical Domains [EMNLP 2020] [[__pdf__](https://arxiv.org/pdf/2010.07717.pdf)][[__code__](https://github.com/RUC-WSM/WD-Match)]
* Transformer Based Multi-Source Domain Adaptation [EMNLP 2020] [[__pdf__](https://arxiv.org/pdf/2009.07806.pdf)][[__code__](https://github.com/copenlu/xformer-multi-source-domain-adaptation)]
* Multi-Stage Pre-training for Low-Resource Domain Adaptation [EMNLP 2020] [[__pdf__](https://arxiv.org/pdf/2010.05904.pdf)]
* Meta Fine-Tuning Neural Language Models for Multi-Domain Text Mining [EMNLP 2020] [[__pdf__](https://arxiv.org/pdf/2003.13003.pdf)]
* Grammatical Error Correction in Low Error Density Domains: A New Benchmark and Analyses [EMNLP 2020] [[__pdf__](https://arxiv.org/pdf/2010.07574.pdf)][[__code__](https://github.com/SimonHFL/CWEB)]
* Feature Adaptation of Pre-Trained Language Models across Languages and Domains with Robust Self-Training [EMNLP 2020] [[__pdf__](https://arxiv.org/pdf/2009.11538.pdf)]
* End-to-End Synthetic Data Generation for Domain Adaptation of Question Answering Systems [EMNLP 2020] [[__pdf__](https://arxiv.org/pdf/2010.06028.pdf)]
* Effective Unsupervised Domain Adaptation with Adversarially Trained Language Models [EMNLP 2020] [[__pdf__](https://arxiv.org/pdf/2010.01739.pdf)][[__code__](https://github.com/trangvu/mlm4uda)]
* An Empirical Investigation Towards Efficient Multi-Domain Language Model Pre-training [EMNLP 2020] [[__pdf__](https://arxiv.org/pdf/2010.00784.pdf)][[__code__](https://github.com/aws-health-ai/multi_domain_lm)]
* MEGATRON-CNTRL: Controllable Story Generation with External Knowledge Using Large-Scale Language Models [EMNLP 2020 main conference] [[__pdf__](https://arxiv.org/pdf/2010.00840.pdf)]



## Survey
* Neural Unsupervised Domain Adaptation in NLP—A Survey [arXiv 2020 May] [[__pdf__](https://arxiv.org/pdf/2006.00632.pdf)]  [[__code__](https://github.com/bplank/awesome-neural-adaptation-in-NLP)]  
* 迁移学习简明手册 Jindong Wang et al. Transfer Learning Tutorial. [[__pdf__](https://tutorial.transferlearning.xyz/)]  

## Theory

## Negative Transfer 
* Characterizing and Avoiding Negative Transfer [CVPR 2019] [[__pdf__](https://arxiv.org/pdf/1811.09751.pdf)]  

## Data Selection
* Reinforced Training Data Selection for Domain Adaptation [ACL 2019] [[__pdf__](https://www.aclweb.org/anthology/P19-1189.pdf)] [[__code__](https://github.com/timerstime/SDG4DA)] 
* Entropy-based Training Data Selection for Domain Adaptation [COLING 2012] [[__pdf__](https://www.aclweb.org/anthology/C12-2116.pdf)]


## Pretraining-based
* Domain-Specific Language Model Pretraining for Biomedical Natural Language Processing [arXiv 2020 Aug] [[__pdf__](https://arxiv.org/pdf/2007.15779.pdf)]  [[__code__](https://microsoft.github.io/BLURB/)] 
* Don’t Stop Pretraining: Adapt Language Models to Domains and Tasks [ACL 2020] [[__pdf__](https://arxiv.org/pdf/2004.10964.pdf)]  [[__code__](https://github.com/allenai/dont-stop-pretraining)] 
* Using Similarity Measures to Select Pretraining Data for NER [NAACL 2019] [[__pdf__](https://arxiv.org/pdf/1904.00585.pdf)]  [[__code__](https://github.com/daixiangau/naacl2019-select-pretraining-data-for-ner)] 
* Unsupervised Domain Clusters in Pretrained Language Models [ACL 2020] [[__pdf__](https://arxiv.org/pdf/2004.02105.pdf)]  [[__code__](https://github.com/roeeaharoni/unsupervised-domain-clusters)] 
* Unsupervised Domain Adaptation of Contextualized Embeddings for Sequence Labeling [EMNLP 2019] [[__pdf__](https://arxiv.org/pdf/1904.02817.pdf)]  [[__code__](https://github.com/xhan77/AdaptaBERT)]  


## Alignment-based
* Curriculum Learning for Domain Adaptation in Neural Machine Translation [NAACL 2019] [[__pdf__](https://arxiv.org/pdf/1905.05816.pdf)]  [[__code__](https://github.com/kevinduh/sockeye-recipes/tree/master/egs/curriculum)] 
* To Annotate or Not? Predicting Performance Drop under Domain Shift  [EMNLP 2019] [[__pdf__](https://www.aclweb.org/anthology/D19-1222.pdf)]  [[__code__](https://github.com/hadyelsahar/domain-shift-prediction)] 
* Active Adversarial Domain Adaptation [WACV 2020] [[__pdf__](https://arxiv.org/pdf/1904.07848.pdf)]
* BatchBALD: Efficient and Diverse Batch Acquisition for Deep Bayesian Active Learning [NeurIPS 2019] [[__pdf__](https://arxiv.org/pdf/1906.08158.pdf)]  [[__code__](https://github.com/BlackHC/BatchBALD)] 
* Multi-Source Domain Adaptation for Text Classification via DistanceNet-Bandits [AAAI 2020] [[__pdf__](https://arxiv.org/pdf/2001.04362.pdf)] 
* Bayesian Uncertainty Matching for Unsupervised Domain Adaptation [IJCAI 2019] [[__pdf__](https://arxiv.org/pdf/1906.09693.pdf)]
* Unsupervised Domain Adaptation via Calibrating Uncertainties [CVPR Workshop 19] [[__pdf__](https://arxiv.org/pdf/1907.11202.pdf)]


# Code Repos
Unsupervised domain adaptation method for relation extraction [[__code__](https://github.com/AnthonyMRios/adversarial-relation-classification)]  
Unsupervised domain adaptation with BERT for Amazon food product reviews sentiment analysis. [[__code__](https://github.com/EmreTaha/Unsupervised-Domain-Adaptation-with-BERT)]
  

# Lectures and Tutorials

# Other Resources
