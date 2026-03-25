# Datasets for AI/ML Projects

> Where to find datasets for your projects — from classic benchmarks to real-world data sources.

[Back to Roadmap](../README.md)

---

## Dataset Platforms

| Platform | Description | Link |
|---|---|---|
| **Kaggle Datasets** | Thousands of community-uploaded datasets with notebooks | [kaggle.com/datasets](https://www.kaggle.com/datasets) |
| **Hugging Face Datasets** | ML-ready datasets with streaming, versioning, and preprocessing | [huggingface.co/datasets](https://huggingface.co/datasets) |
| **UCI ML Repository** | Classic academic ML datasets | [archive.ics.uci.edu](https://archive.ics.uci.edu/) |
| **Google Dataset Search** | Search engine for datasets | [datasetsearch.research.google.com](https://datasetsearch.research.google.com/) |
| **Papers With Code Datasets** | Datasets linked to benchmarks and papers | [paperswithcode.com/datasets](https://paperswithcode.com/datasets) |
| **AWS Open Data** | Large-scale public datasets | [registry.opendata.aws](https://registry.opendata.aws/) |
| **data.gov** | US government open data | [data.gov](https://data.gov/) |

## Classic ML Datasets

| Dataset | Task | Size | Good For |
|---|---|---|---|
| **Iris** | Classification | 150 samples | First classification project |
| **Titanic** | Classification | ~900 samples | Feature engineering, missing data |
| **Boston Housing** / California Housing | Regression | ~500 / 20k samples | Regression basics |
| **MNIST** | Image classification | 70k images | First deep learning project |
| **CIFAR-10/100** | Image classification | 60k images | CNN benchmarking |
| **Wine Quality** | Regression/Classification | ~6k samples | Multi-class, feature engineering |
| **Adult Census Income** | Classification | ~48k samples | Fairness, bias analysis |

## NLP Datasets

| Dataset | Task | Description |
|---|---|---|
| **IMDb Reviews** | Sentiment analysis | 50k movie reviews with labels |
| **SQuAD** | Question answering | 100k+ question-answer pairs from Wikipedia |
| **GLUE / SuperGLUE** | NLU benchmark | Multi-task language understanding |
| **Common Crawl** | Pretraining | Massive web crawl (petabytes) |
| **The Pile** | Pretraining | Curated diverse text corpus |
| **Alpaca / OpenAssistant** | Instruction tuning | Instruction-response pairs for SFT |
| **WMT** | Translation | Parallel text in many language pairs |

## Computer Vision Datasets

| Dataset | Task | Description |
|---|---|---|
| **ImageNet** | Classification | 14M+ images, 21k categories |
| **COCO** | Detection, segmentation, captioning | 330k images with rich annotations |
| **Pascal VOC** | Detection, segmentation | Classic detection benchmark |
| **Open Images** | Detection, classification | 9M images from Google |
| **Cityscapes** | Autonomous driving | Urban scene segmentation |
| **CelebA** | Face attributes | 200k celebrity face images |
| **LAION** | Image-text pairs | Billions of image-text pairs (for diffusion model training) |

## Audio Datasets

| Dataset | Task | Description |
|---|---|---|
| **LibriSpeech** | Speech recognition | 1000 hours of English audiobooks |
| **Common Voice** | Speech recognition | Crowdsourced multilingual speech |
| **AudioSet** | Audio classification | 2M+ YouTube clips with labels |
| **MUSDB18** | Source separation | Multi-track music for separation |

## Reinforcement Learning Environments

| Environment | Description | Link |
|---|---|---|
| **Gymnasium (Atari, MuJoCo)** | Classic RL benchmarks | [gymnasium.farama.org](https://gymnasium.farama.org/) |
| **PettingZoo** | Multi-agent environments | [pettingzoo.farama.org](https://pettingzoo.farama.org/) |
| **MineRL** | Minecraft-based RL | [minerl.io](https://minerl.io/) |

## Tabular / Business Datasets

| Dataset | Task | Description |
|---|---|---|
| **Telco Customer Churn** | Churn prediction | Customer behavior data |
| **Credit Card Fraud** | Fraud detection | Highly imbalanced transaction data |
| **Ames Housing** | Price prediction | Detailed housing features |
| **Retail Sales** | Time series forecasting | Store sales data |
| **NYC Taxi** | Regression, geospatial | Trip data with timing and location |

---

## Tips for Working with Datasets

1. **Start small** — use classic datasets to learn techniques before scaling up
2. **Check licenses** — some datasets have restrictions on commercial use
3. **Use Hugging Face `datasets`** library for easy loading and streaming:
   ```python
   from datasets import load_dataset
   dataset = load_dataset("imdb")
   ```
4. **Version your data** — use DVC or Hugging Face to track dataset versions
5. **Create your own** — web scraping, APIs, and synthetic data generation are valuable skills
