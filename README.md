# Awesome-Large-Models-for-Time-Series

## SOTA
| Venue   | Title                                                        |
| ------- | ------------------------------------------------------------ |
|  | [SOFTS: Efficient Multivariate Time Series Forecasting with Series-Core Fusion](https://arxiv.org/pdf/2404.14197) |
|  | [Are Self-Attentions Effective for Time Series Forecasting?](https://arxiv.org/pdf/2405.16877) |
|  | [In-context Time Series Predictor](https://arxiv.org/pdf/2405.14982) |


## Survey

| Venue   | Title                                                        |
| ------- | ------------------------------------------------------------ |
| ICML'24 | [Position: What Can Large Language Models Tell Us about Time Series Analysis](https://openreview.net/pdf?id=iroZNDxFJZ) |
| KDD'24  | [Foundation Models for Time Series Analysis: A Tutorial and Survey](https://arxiv.org/pdf/2403.14735) |

## Training

### Pre-Training

| Venue   | Title                                                        | Keywords                                                |
| ------- | ------------------------------------------------------------ | ------------------------------------------------------- |
| ICML'24 | [Unified Training of Universal Time Series Forecasting Transformers](https://arxiv.org/pdf/2402.02592) | Multivariate; Large-scale data; Variable window size    |
| ICML’24 | [Timer: Generative Pre-trained Transformers Are Large Time Series Models](https://openreview.net/pdf?id=bYRYb7DMNo) | Channel independence; Large-scale data; Auto-regression |
| arXiv’24 | [UNITS: A Unified Multi-Task Time Series Model](https://arxiv.org/pdf/2403.00131) | One model for many tasks; Prompt tuning |
| ICML'24 | [MOMENT: A Family of Open Time-series Foundation Models](https://openreview.net/pdf?id=FVvf69a5rx) | Masked auto-encoder pretraining                         |
| ICML'24 | [A decoder-only foundation model for time-series forecasting](https://openreview.net/pdf?id=jn2iTJas6h) | Auto-regressive patch-wise decoding                     |
| ICML'24 | [TimeSiam: A Pre-Training Framework for Siamese Time-Series Modeling](https://openreview.net/pdf?id=wrTzLoqbCg) | Reconstruction                                          |

### Fine-Tuning

### Pre-Training & Fine-Tuning

| Venue   | Title                                                        | Keywords                                                     |
| ------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| ICML'24 | [UP2ME: Univariate Pre-training to Multivariate Fine-tuning as a General-purpose Framework for Multivariate Time Series Analysis](https://openreview.net/pdf?id=aR3uxWlZhX) | Masked auto-encoder pretraining; Variable window size; Multivariate fine-tuning |
| ICML'24 | [Multi-Patch Prediction: Adapting LLMs for Time Series Representation Learning](https://arxiv.org/pdf/2402.04852v2) | Autoregressive patch-wise decoding                           |

## Prompting / Conditional Generation

| Venue   | Title                                                        | Keywords                 |
| ------- | ------------------------------------------------------------ | ------------------------ |
| ICML'24 | [Time Weaver: A Conditional Time Series Generation Model](https://openreview.net/pdf?id=WpKDeixmFr) | Diffusion                |
| ICML'24 | [S$^2$IP-LLM: Semantic Space Informed Prompt Learning with LLM for Time Series Forecasting](https://arxiv.org/pdf/2403.05798) | Retrieve word embeddings |
| KDD'24  | [POND: Multi-Source Time Series Domain Adaptation with Information-Aware Prompt Tuning](https://arxiv.org/pdf/2312.12276) | Transfer |

# Misc

### Lightweight

| Venue   | Title                                                        | Keywords           |
| ------- | ------------------------------------------------------------ | ------------------ |
| ICML'24 | [An Analysis of Linear Time Series Forecasting Models](https://openreview.net/pdf?id=xl82CcbYaT) | Mathematical proof |
| ICML'24 | [SparseTSF: Modeling Long-term Time Series Forecasting with 1k Parameters](https://openreview.net/pdf?id=54NSHO0lFe) |                    |

### Non-stationary

| Venue   | Title                                                        | Keywords |
| ------- | ------------------------------------------------------------ | -------- |
| ICML'24 | [SIN: Selective and Interpretable Normalization for Long-Term Time Series Forecasting](https://openreview.net/pdf?id=cUMOVfOIve) |          |

### Generalization

| Venue   | Title                                                        | Keywords |
| ------- | ------------------------------------------------------------ | -------- |
| ICML'24 | [Time-Series Forecasting for Out-of-Distribution Generalization Using Invariant Learning](https://openreview.net/pdf?id=SMUXPVKUBg) |          |

### Channel Dependence

| Venue   | Title                                                        | Keywords |
| ------- | ------------------------------------------------------------ | -------- |
| ICML'24 | [CATS: Enhancing Multivariate Time Series Forecasting by Constructing Auxiliary Time Series as Exogenous Variables](https://openreview.net/pdf?id=1lDAGDe0UR) |          |

### Multi-Modal

| Venue   | Title                                                        | Keywords     |
| ------- | ------------------------------------------------------------ | ------------ |
|         | [MoAT: Multi-Modal Augmented Time Series Forecasting](https://openreview.net/forum?id=uRXxnoqDHH) | News article |
