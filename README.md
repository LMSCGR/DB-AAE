## DB-AAE (Adversarial Autoencoder with dynamic batching )
### Abstract

By revealing the transcriptome of individual cells, single-cell RNA sequencing (scRNA-seq) offers insights into cellular heterogeneity and disease mechanisms. However, challenges such as low capture rates and dropout events can introduce noise in data analysis. Here, we propose a generative framework, the dynamic batching adversarial autoencoder (DB-AAE), which excels at denoising in scRNA-seq datasets. DB-AAE directly captures optimal features from input data and enhances feature preservation, including cell type-specific gene expression patterns. Comprehensive evaluation on simulated and real datasets demonstrates that DB-AAE outperforms other methods in denoising accuracy and biological signal preservation. It also improves the accuracy of other algorithms in establishing pseudo-time inference. This study highlights DB-AAE's effectiveness and potential as a valuable tool for enhancing the quality and reliability of downstream analyses in scRNA-seq research.

### Dataset
#### Spacial
Gdrive : https://drive.google.com/drive/folders/1DwRpIEStBTQ7XfAel7Qq1uJeCRZyUj9U?usp=sharing

#### Temperal
Gdrive : https://drive.google.com/drive/folders/1yciRZ-b8r27JcEsE_g0N99tPDMzSfTpe?usp=sharing

### Codes
#### Enviroment
- Python 3.8
- scanpy 1.9.1
- seaborn 0.12.2
- pandas 1.5.3
- matplotlib 3.6.3
- numpy 1.23.5
- tensorflow 2.11.0
- keras-tuner 1.4.5
- keras 2.15.0
#### Installation

##### pip

For a traditional Python installation, use

```
$ pip install "$package name"
```
#### Usage
