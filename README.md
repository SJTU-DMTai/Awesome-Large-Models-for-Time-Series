# Awesome-Large-Models-for-Time-Series

## SOTA
| Venue   | Title                                                        |
| ------- | ------------------------------------------------------------ |
| Under review of ICLR'25 | [Time-MoE: Billion-Scale Time Series Foundation Models with Mixture of Experts](https://arxiv.org/pdf/2409.16040) |
| Under review of ICLR'25 | [In-context Time Series Predictor](https://arxiv.org/pdf/2405.14982) |
| NIPS'24 | [SOFTS: Efficient Multivariate Time Series Forecasting with Series-Core Fusion](https://arxiv.org/pdf/2404.14197) |
| NIPS'24 | [Are Self-Attentions Effective for Time Series Forecasting?](https://arxiv.org/pdf/2405.16877) |


## Survey

| Venue   | Title                                                        |
| ------- | ------------------------------------------------------------ |
| ICML'24 | [Position: What Can Large Language Models Tell Us about Time Series Analysis](https://openreview.net/pdf?id=iroZNDxFJZ) |
| KDD'24  | [Foundation Models for Time Series Analysis: A Tutorial and Survey](https://arxiv.org/pdf/2403.14735) |

## Benchmark

| Venue   | Title                                                        | Keywords                                                     |
| ------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Under Review of ICLR'25 | [FoundTS: Comprehensive and Unified Benchmarking of Foundation Models for Time Series Forecasting](https://openreview.net/forum?id=B4OaA0aJ4Z) | |
| Under Review of ICLR'25 | [GIFT-Eval: A Benchmark for General Time Series Forecasting Model Evaluation](https://openreview.net/forum?id=9EBSEkFSje) | |

## Training

### Pretrained Foundation Models

| Venue   | Title                                                        | Keywords                                                |
| ------- | ------------------------------------------------------------ | ------------------------------------------------------- |
| Under Review of ICLR'25 | [Moirai-MoE: Empowering Time Series Foundation Models with Sparse Mixture of Experts](https://openreview.net/forum?id=HbbnlrmsAH) | |
| Under Review of ICLR'25 | [FlexTSF: A universal forecasting model for time series with variable regularities](https://openreview.net/forum?id=LuLzcBsp5c) | |
| Under Review of ICLR'25 | [Towards Generalisable Time Series Understanding Across Domains](https://openreview.net/forum?id=39n570rxyO) | |
| NIPS'24 | [Large Pre-trained time series models for cross-domain Time series analysis tasks](https://arxiv.org/abs/2311.11413) | |
| NIPS’24 | [UNITS: A Unified Multi-Task Time Series Model](https://arxiv.org/pdf/2403.00131) | One model for many tasks; Prompt tuning |
| ICML'24 | [Unified Training of Universal Time Series Forecasting Transformers](https://arxiv.org/pdf/2402.02592) | Multivariate; Large-scale data; Variable window size    |
| ICML’24 | [Timer: Generative Pre-trained Transformers Are Large Time Series Models](https://openreview.net/pdf?id=bYRYb7DMNo) | Channel independence; Large-scale data; Auto-regression |
| ICML'24 | [MOMENT: A Family of Open Time-series Foundation Models](https://openreview.net/pdf?id=FVvf69a5rx) | Masked auto-encoder pretraining                         |
| ICML'24 | [A decoder-only foundation model for time-series forecasting](https://openreview.net/pdf?id=jn2iTJas6h) | Auto-regressive patch-wise decoding                     |

#### Special Designs

| Venue   | Title                                                        | Keywords                                                     |
| ------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Under Review of ICLR'25 | [Enhancing Foundation Models for Time Series Forecasting via Wavelet-based Tokenization](https://openreview.net/forum?id=D9liZ0D8z8) | |
| Under Review of ICLR'25 | [Towards Adaptive Time Series Foundation Models Against Distribution Shift](https://openreview.net/forum?id=YhIpTdrUDY) | |

### Fine-Tuning
| Venue   | Title                                                        | Keywords                                                     |
| ------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Under Review of ICLR'25 | [In-context Fine-tuning for Time-series Foundation Models](https://openreview.net/forum?id=ryIHtXE9uG) | |
| Under Review of ICLR'25 | []() | |

### Pre-Training & Fine-Tuning

| Venue   | Title                                                        | Keywords                                                     |
| ------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| ICML'24 | [UP2ME: Univariate Pre-training to Multivariate Fine-tuning as a General-purpose Framework for Multivariate Time Series Analysis](https://openreview.net/pdf?id=aR3uxWlZhX) | Masked auto-encoder pretraining; Variable window size; Multivariate fine-tuning |
| ICML'24 | [Multi-Patch Prediction: Adapting LLMs for Time Series Representation Learning](https://arxiv.org/pdf/2402.04852v2) | Autoregressive patch-wise decoding                           |

## Prompting / Conditional Generation

| Venue   | Title                                                        | Keywords                 |
| ------- | ------------------------------------------------------------ | ------------------------ |
| Under Review of ICLR'25 | [TimeRAF: Retrieval-Augmented Foundation model for Zero-shot Time Series Forecasting](https://openreview.net/forum?id=zd5Knrtja4) | |
| Under Review of ICLR'25 | [TimeRAG: It's Time for Retrieval-Augmented Generation in Time-Series Forecasting](https://openreview.net/forum?id=GvzL4LuycW) | |
| Under Review of ICLR'25 | [Retrieval Augmented Time Series Forecasting](https://openreview.net/forum?id=GYwH71ugtC) | |
| Under Review of ICLR'25 | [CRAFT: Time Series Forecasting with Cross-Future Behavior Awareness](https://openreview.net/forum?id=PLYqJVV7dm) | |
| Under Review of ICLR'25 | [Metadata Matters for Time Series: Informative Forecasting with Transformers](https://openreview.net/forum?id=NJqsHgxcKh) | |
| ICML'24 | [Time Weaver: A Conditional Time Series Generation Model](https://openreview.net/pdf?id=WpKDeixmFr) | Diffusion                |
| ICML'24 | [S$^2$IP-LLM: Semantic Space Informed Prompt Learning with LLM for Time Series Forecasting](https://arxiv.org/pdf/2403.05798) | Retrieve word embeddings |
| KDD'24  | [POND: Multi-Source Time Series Domain Adaptation with Information-Aware Prompt Tuning](https://arxiv.org/pdf/2312.12276) | Transfer |

## Long-context
| Venue   | Title                                                        | Keywords                                                     |
| ------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Under Review of ICLR'25 | [Timer-XL: Long-Context Transformers for Unified Time Series Forecasting](https://openreview.net/forum?id=KMCJXjlDDr) | |

# Misc

### Lightweight

| Venue   | Title                                                        | Keywords           |
| ------- | ------------------------------------------------------------ | ------------------ |
| Under Review of ICLR'25 | [FastTF: 4 Parameters are All You Need for Long-term Time Series Forecasting](https://openreview.net/forum?id=CZiP7GpmX7) |  |
| ICML'24 | [SparseTSF: Modeling Long-term Time Series Forecasting with 1k Parameters](https://openreview.net/pdf?id=54NSHO0lFe) |                    |

### Non-stationary

| Venue   | Title                                                        | Keywords |
| ------- | ------------------------------------------------------------ | -------- |
| ICML'24 | [SIN: Selective and Interpretable Normalization for Long-Term Time Series Forecasting](https://openreview.net/pdf?id=cUMOVfOIve) |          |

### Multi-Modal

| Venue   | Title                                                        | Keywords     |
| ------- | ------------------------------------------------------------ | ------------ |
| NIPS'24 | [Time-MMD: A New Multi-Domain Multimodal Dataset for Time Series Analysis](https://arxiv.org/abs/2406.08627) | |
|         | [MoAT: Multi-Modal Augmented Time Series Forecasting](https://openreview.net/forum?id=uRXxnoqDHH) | News article |
