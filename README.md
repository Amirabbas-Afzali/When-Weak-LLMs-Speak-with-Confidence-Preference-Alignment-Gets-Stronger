# When Weak LLMs Speak with Confidence, Preference Alignment Gets Stronger

This repository will contain the code (**coming soon**) for the paper:

**When Weak LLMs Speak with Confidence, Preference Alignment Gets Stronger** ([OpenReview](https://openreview.net/forum?id=ROioaZ45Yz), [pdf](https://openreview.net/pdf?id=ROioaZ45Yz))  
*In Proceedings of the International Conference on Learning Representations (ICLR), 2026*

## Abstract

Preference alignment is an essential step in adapting large language models (LLMs) to human values, but existing approaches typically depend on costly human annotations or large-scale API-based models. We explore whether a weak LLM can instead act as an effective annotator. We surprisingly find that selecting only a subset of a weak LLM's highly confident samples leads to substantially better performance than using full human annotations. Building on this insight, we propose **Confidence-Weighted Preference Optimization (CW-PO)**, a general framework that re-weights training samples by a weak LLM’s confidence and can be applied across different preference optimization objectives. Notably, the model aligned by CW-PO with just 20% of human annotations outperforms the model trained with 100% of annotations under standard DPO. These results suggest that weak LLMs, when paired with confidence weighting, can dramatically reduce the cost of preference alignment while even outperforming methods trained on fully human-labeled data.

## Code

The training and evaluation code will be released soon.  

## Citation

If you use this repository in your research, please cite our paper:
```
@inproceedings{
afzali2026when,
title={When Weak {LLM}s Speak with Confidence, Preference Alignment Gets Stronger},
author={Amirabbas Afzali and Myeongho Jeon and Maria Brbic},
booktitle={The Fourteenth International Conference on Learning Representations},
year={2026},
url={https://openreview.net/forum?id=ROioaZ45Yz}
}
```
