# Meta-Learning-for-few-shot-classification
WACV2020: Class-Discriminative Feature Embedding For Meta-Learning based Few-Shot Classification

Although deep learning-based approaches have been very effective in solving problems with plenty of labeled
data, they suffer in tackling problems for which labeled data
are scarce. In few-shot classification, the objective is to
train a classifier from only a handful of labeled examples
in a support set. In this paper, we propose a few-shot learning framework based on structured margin loss which takes
into account the global structure of the support set in order to generate a highly discriminative feature space where
the features from distinct classes are well separated in clusters. Moreover, in our meta-learning-based framework, we
propose a context-aware query embedding encoder for incorporating support set context into query embedding and
generating more discriminative and task-dependent query
embeddings. The task-dependent features help the meta learner to learn a distribution over tasks more effectively.
Extensive experiments based on few-shot, zero-shot, and
semi-supervised learning on three benchmarks show the advantages of the proposed model compared to state-of-the art.

Paper: [Class-Discriminative Feature Embedding For Meta-Learning based Few-Shot Classification](https://openaccess.thecvf.com/content_WACV_2020/html/Rahimpour_Class-Discriminative_Feature_Embedding_For_Meta-Learning_based_Few-Shot_Classification_WACV_2020_paper.html)

<img width="424" alt="image" src="https://github.com/AlirezaRahimpour/Meta-Learning-for-few-shot-classification/assets/18356361/80069dc7-3f7e-4bae-8bb8-9a998bb8ac4f">

The main contributions of this work are as follows:

-  Regularizing the few-shot classification setting with a
structured-based margin loss which takes into account
the global structure of the support set feature space and
learns to explicitly reduce the intra-class variation in
order to map the data to a highly discriminative feature
space where the few-shot classification is most effective.

- Proposing a context-aware query embedding module
which takes into account the support set’s context
and generates task-dependent feature representations
which would help the meta-learner to learn a distribution over tasks more effectively.

-  Performing extensive experiments based on few-shot, one-shot, zero-shot, and semi-supervised learning
schemes to show the advantages of the proposed model
compared to the state-of-the-art.

<img width="854" alt="image" src="https://github.com/AlirezaRahimpour/Meta-Learning-for-few-shot-classification/assets/18356361/4c03f85e-6791-45df-b8ab-5276baae74ba">

More details coming soon! :) 

## Citation 

If you find this work useful, please consider citing:  

```bibtex
@InProceedings{Rahimpour_2020_WACV,
author = {Rahimpour, Alireza and Qi, Hairong},
title = {Class-Discriminative Feature Embedding For Meta-Learning based Few-Shot Classification},
booktitle = {Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)},
month = {March},
year = {2020}
}
```
