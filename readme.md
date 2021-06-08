# Awesome Medication Recommendation [![](https://awesome.re/badge.svg)](https://awesome.re)[![License:  CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

> A curated list of awesome research on medication recommendation


## Contents

- [Instance-based methods](#instance-based-methods)
- [Longitudinal-based methods](#longitudinal-based-methods)
- [Others](#others)
- [Datasets](#datasets)
- [Contribute](#contribute)


## Instance-based methods

> Instance-based methods focus on the patient’s current health status.

- LEAP: Learning to Prescribe Effective and Safe Treatment Combinations for Multimorbidity [`scholar`](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=LEAP%3A+Learning+to+Prescribe+Effective+and+Safe+Treatment+Combinations+for+Multimorbidity&btnG=) [`KDD 2017`](https://dl.acm.org/doi/abs/10.1145/3097983.3098109) [`code`](https://github.com/neozhangthe1/AutoPrescribe)
- SMR: Medical Knowledge Graph Embedding for Safe Medicine Recommendation [`scholar`](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=SMR%3A+Medical+Knowledge+Graph+Embedding+for+Safe+Medicine+Recommendation&btnG=) [`Big Data Research 2021`](https://www.sciencedirect.com/science/article/pii/S2214579620300423?casa_token=1dbnf7YJj60AAAAA:y-ojXslZzSeul6QPIG7MGMl_5XSo4Bc3OSoFsdAW-8LOKTzIRIdGu1EeMUyM09HkdcL5yYvNQao)

## Longitudinal-based  methods

> Longitudinal-based  methods  leverage  the  temporal  dependencies  among  clinical  event.

- Dual memory neural computer for asynchronous two-view sequential learning [`scholar`](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Dual+memory+neural+computer+for+asynchronous+two-view+sequential+learning&btnG=)  [`KDD 2018`](https://dl.acm.org/doi/abs/10.1145/3219819.3219981) [`code`](https://github.com/thaihungle/DMNC)
- GAMENet：Graph Augmented MEmory Networks for Recommending Medication Combination [`scholar`](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=GAMENet%EF%BC%9AGraph+Augmented+MEmory+Networks+for+Recommending+Medication+Combination&btnG=)  [`AAAI 2019`](https://ojs.aaai.org/index.php/AAAI/article/view/3905) [`code`](https://github.com/sjy1203/GAMENet)
- Order-free Medicine Combination Prediction with Graph Convolutional Reinforcement Learning [`scholar`](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Order-free+Medicine+Combination+Prediction+with+Graph+Convolutional+Reinforcement+Learning&btnG=) [`CIKM 2019`](https://dl.acm.org/doi/abs/10.1145/3357384.3357965) [`code`](https://github.com/WOW5678/CompNet)
- PREMIER: Personalized REcommendation for Medical prescrIptions from Electronic Records [`scholar`](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=PREMIER%3A+Personalized+REcommendation+for+Medical+prescrIptions+from+Electronic+Records&btnG=)  [`arXiv 2020`](https://arxiv.org/abs/2008.13569)
- RETAIN: An Interpretable Predictive Model for Healthcare using Reverse Time Attention Mechanism [`scholar`](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=RETAIN%3A+An+Interpretable+Predictive+Model+for+Healthcare+using+Reverse+Time+Attention+Mechanism&btnG=) [`arXiv 2016`](https://arxiv.org/abs/1608.05745) [`code`](https://github.com/mp2893/retain)
- Supervised Reinforcement Learning with Recurrent Neural Network for Dynamic Treatment Recommendation [`scholar`](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Supervised+Reinforcement+Learning+with+Recurrent+Neural+Network+for+Dynamic+Treatment+Recommendation&btnG=) [`KDD 2018`](https://dl.acm.org/doi/abs/10.1145/3219819.3219961) [`code`](https://github.com/Joywanglulu/SRL_DTR)

## Others

- Adversarially regularized medication recommendation model with multi-hop memory network [`scholar`](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Adversarially+regularized+medication+recommendation+model+with+multi-hop+memory+network&btnG=) [`KAIS 2021`](https://link.springer.com/article/10.1007/s10115-020-01513-9) [`code`](https://github.com/yanda-wang/ARMR)
- Change Matters: Medication Change Prediction with Recurrent Residual Networks [`scholar`](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Change+Matters%3A+Medication+Change+Prediction+with+Recurrent+Residual+Networks&btnG=) [`arXiv 2021`](https://arxiv.org/abs/2105.01876)
- GATE: Graph-Attention Augmented Temporal Neural Network for Medication Recommendation [`scholar`](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=GATE%3A+Graph-Attention+Augmented+Temporal+Neural+Network+for+Medication+Recommendation&btnG=) [`IEEE 2020`](https://ieeexplore.ieee.org/abstract/document/9134772/)
- Pre-training of Graph Augmented Transformers for Medication Recommendation [`scholar`](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Pre-training+of+Graph+Augmented+Transformers+for+Medication+Recommendation&btnG=) [`arXiv 2019`](https://arxiv.org/abs/1906.00346) [`code`](https://github.com/jshang123/G-Bert)
- SafeDrug: Dual Molecular Graph Encoders for Safe Drug Recommendations [`scholar`](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=SafeDrug%3A+Dual+Molecular+Graph+Encoders+for+Safe+Drug+Recommendations&btnG=) [`arXiv 2021`](https://arxiv.org/abs/2105.02711) [`code`](https://github.com/ycq091044/SafeDrug)

## Datasets

> Datasets used in medication recommendation.

- [MIMIC Critical Care Database](https://mimic.physionet.org/) - Medical Information Mart for Intensive Care.
- [DDI Data](https://www.dropbox.com/s/8os4pd2zmp2jemd/drug-DDI.csv?dl=0) - Drug-Drug Interaction Data.
- [DrugBank](https://www.drugbank.com/) - A curated pharmaceutical knowledge base, with products commercially available for precision medicine, telehealth, and drug discovery.


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.