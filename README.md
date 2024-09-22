# Awesome Phenotypic Drug Discovery (PDD)

If you have any problems, suggestions or improvements, please submit the issue or PR.

## Contents
* [Survey](#survey)
* [Datasets](#datasets)
* [Tools](#Tools)


## Papers

Considering the increasing number of papers in this field, we roughly summarize some articles and put them into the following categories:

| [[**Image-based PDD**](##Image-based_PDD)] | [[**Gene-based PDD**](Gene-based_PDD)] | [[**Image & Gene-based PDD**](##Image&Gene-based_PDD)] |
| :---- | :---- | :---- |
| [[**Image & Other-based PDD**](##Image&Other-based_PDD)] | [[**Image, Gene & Other-based PDD**](##Image&Gene&Other-based_PDD)] | [[**Multi-channel Image Processing**](##Multi-channel_Image_Processing)] |


# Survey
- <a name=""></a>**[2024]** Morphological profiling for drug discovery in the era of deep learning (**Briefings in Bioinformatics**) [[paper](https://academic.oup.com/bib/article/25/4/bbae284/7693952)]
- <a name=""></a>**[2024]** Artificial intelligence for high content imaging in drug discovery (**Current Opinion in Structural Biology**) [[paper](https://www.nature.com/articles/s41467-024-45999-1)]
- <a name=""></a>**[2023]** Deep learning in image-based phenotypic drug discovery (**Trends in Cell Biology**) [[paper](https://www.cell.com/trends/cell-biology/abstract/S0962-8924(22)00262-8)]
- <a name=""></a>**[2022]** Phenotypic drug discovery: recent successes, lessons learned and new directions (**Nature Reviews Drug Discovery**) [[paper](https://www.nature.com/articles/s41573-022-00472-w)]
- <a name=""></a>**[2020]** Image-based profiling for drug discovery: due for a machine-learning upgrade? (**Nature Reviews Drug Discovery**) [[paper](https://www.nature.com/articles/s41573-020-00117-w)]


# Datasets
- <a name=""></a>**[Cell Painting Gallery]** [[Link](https://registry.opendata.aws/cellpainting-gallery/)]  [[Datasets Overview](https://github.com/broadinstitute/cellpainting-gallery/blob/main/README.md)]  [[AWS Overview](https://cellpainting-gallery.s3.amazonaws.com/index.html)]
- <a name=""></a>**[JUMP-Cell Painting Consortium]** [[Link](https://jump-cellpainting.broadinstitute.org/)]
- <a name=""></a>**[NYSCF Automated Deep Phenotyping Dataset (ADPD)]** [[Link](https://nyscf.org/open-source/nyscf-adpd/)]


# Tools
- <a name=""></a>**[DeepProfiler]** Learning representations for image-based profiling of perturbations (**Nature Communications**) [[paper](https://www.nature.com/articles/s41467-024-45999-1)] [[code](https://github.com/cytomining/DeepProfiler)]![GitHub stars](https://img.shields.io/github/stars/cytomining/DeepProfiler.svg?logo=github&label=Stars)
- <a name=""></a> **[Pycytominer]** Reproducible image-based profiling with Pycytominer (**Arxiv**) [[paper](https://arxiv.org/abs/2311.13417)] [[code](https://github.com/cytomining/pycytominer)]![GitHub stars](https://img.shields.io/github/stars/cytomining/pycytominer.svg?logo=github&label=Stars)
- <a name=""></a> **[CellProfiler]** CellProfiler 3.0:Next-generation imageprocessing for biology (**PLOS BIOLOGY**) [[paper](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.2005970)] [[code](https://github.com/CellProfiler)]![GitHub stars](https://img.shields.io/github/stars/CellProfiler/CellProfiler.svg?logo=github&label=Stars)


# Papers

## Image-based_PDD
<details>
<summary>Details</summary>

### 2024
- <a name=""></a>**[Batch Correction]** Evaluating batch correction methods for image-based cell profiling (**Nature Communications**) [[paper](https://www.nature.com/articles/s41467-024-50613-5)] [[code](https://github.com/carpenter-singh-lab/2023_Arevalo_BatchCorrection)]![GitHub stars](https://img.shields.io/github/stars/carpenter-singh-lab/2023_Arevalo_BatchCorrection.svg?logo=github&label=Stars)

- <a name=""></a>**[scDINO]** Self-supervised vision transformers accurately decode cellular state heterogeneity (** BioRxiv **) [[paper](https://www.biorxiv.org/content/10.1101/2023.01.16.524226v1)][[code](https://github.com/JacobHanimann/scDINO)]![GitHub stars](https://img.shields.io/github/stars/JacobHanimann/scDINO.svg?logo=github&label=Stars)


### 2023

- <a name=""></a> Deep representation learning determines drug mechanism of action from cell painting images (**Digital Discovery**) [[paper](https://pubs.rsc.org/en/content/articlelanding/2023/dd/d3dd00060e)] [[code](https://github.com/pfizer-opensource/moa-profiler)]![GitHub stars](https://img.shields.io/github/stars/pfizer-opensource/moa-profiler.svg?logo=github&label=Stars)

### 2022

- <a name=""></a> **[Dataset]** Integrating deep learning and unbiased automated high-content screening to identify complex disease signatures in human fibroblasts (**Nature Communications**) [[paper](https://www.nature.com/articles/s41467-022-28423-4)] [[dataset](https://nyscf.org/open-source/nyscf-adpd/)]

- <a name=""></a> **[WS-DINO]** Self-Supervised Learning of Phenotypic Representations from Cell Images with Weak Labels (**LMRL @NeurIPS 2022**) [[paper](https://arxiv.org/abs/2209.07819)] [[code](https://github.com/crosszamirski/WS-DINO/)]![GitHub stars](https://img.shields.io/github/stars/crosszamirski/WS-DINO.svg?logo=github&label=Stars)


</details>

## Gene-based_PDD
<details>
<summary>Details</summary>

### 2024
- <a name=""></a>**[PERCEPTION]** PERCEPTION predicts patient response and resistance to treatment using single-cell transcriptomics of their tumors (**Nature Cancer**) [[paper](https://www.nature.com/articles/s43018-024-00756-7)] [[code](https://github.com/ruppinlab/PERCEPTION)]![GitHub stars](https://img.shields.io/github/stars/ruppinlab/PERCEPTION.svg?logo=github&label=Stars)

### 2023

- <a name=""></a>**[SCAD]** Enabling Single-Cell Drug Response Annotations from Bulk RNA-Seq Using SCAD (**Advanced Science**) [[paper](https://onlinelibrary.wiley.com/doi/10.1002/advs.202204113)] [[code](https://github.com/CompBioT/SCAD)]![GitHub stars](https://img.shields.io/github/stars/CompBioT/SCAD.svg?logo=github&label=Stars)

- <a name=""></a>**[ASGARD]** ASGARD is A Single-cell Guided Pipeline to Aid Repurposing of Drugs (**Nature Communications**) [[paper](https://www.nature.com/articles/s41467-023-36637-3)] [[code](https://github.com/lanagarmire/ASGARD)]![GitHub stars](https://img.shields.io/github/stars/lanagarmire/ASGARD.svg?logo=github&label=Stars)

### 2021 and before
- <a name=""></a>**[Velodrome]** Out-of-distribution generalization from labelled and unlabelled gene expression data for drug response prediction (**Nature Machine Intelligence**) [[paper](https://www.nature.com/articles/s43018-024-00756-7)] [[code](https://github.com/hosseinshn/Velodrome)]![GitHub stars](https://img.shields.io/github/stars/hosseinshn/Velodrome.svg?logo=github&label=Stars)




</details>

## Image&Gene-based_PDD
<details>
<summary>Details</summary>

### 2024

### 2023

</details>


## Image&Other-based_PDD
<details>
<summary>Details</summary>

### 2024
- <a name=""></a>**[MIGA]** Cross-Modal Graph Contrastive Learning with Cellular Images (**Advanced science**) [[paper](https://onlinelibrary.wiley.com/doi/full/10.1002/advs.202404845)] [[code](https://github.com/prokia/MIGA)]![GitHub stars](https://img.shields.io/github/stars/prokia/MIGA.svg?logo=github&label=Stars)

### 2023

### 2022
- <a name=""></a> **[Contrastive learning]** Contrastive learning of image- and structure-based representations in drug discovery (**MLDD @ICLR 2022**) [[paper](https://openreview.net/pdf?id=OdXKRtg1OG)] [[code](https://github.com/ml-jku/cloome)]![GitHub stars](https://img.shields.io/github/stars/ml-jku/cloome.svg?logo=github&label=Stars)

</details>

## Image&Gene&Other-based_PDD
<details>
<summary>Details</summary>

### 2024

- <a name=""></a>**[Datasets]** JUMP Cell Painting dataset: morphological impact of 136,000 chemical and genetic perturbations (**Arxiv**) [[paper](https://www.biorxiv.org/content/10.1101/2023.03.23.534023v2)] [[dataset](https://registry.opendata.aws/cellpainting-gallery/)]

- <a name=""></a>**[Datasets and Benchmark]** Three million images and morphological profiles of cells treated with matched chemical and genetic perturbations (**Nature Methods**) [[paper](https://www.nature.com/articles/s41592-024-02241-6)] [[code](https://github.com/jump-cellpainting/2024_Chandrasekaran_NatureMethods/tree/main)]![GitHub stars](https://img.shields.io/github/stars/jump-cellpainting/2024_Chandrasekaran_NatureMethods.svg?logo=github&label=Stars)

### 2023

- <a name=""></a>**[Multimodal]** Multimodal data fusion for cancer biomarker discovery with deep learning (**Nature Machine Intelligence**) [[paper](https://www.nature.com/articles/s42256-023-00633-5)]

- <a name=""></a>**[Multimodal]** Predicting compound activity from phenotypic profiles and chemical structures (**Nature Communications**) [[paper](https://www.nature.com/articles/s41467-023-37570-1)] [[code](https://github.com/CaicedoLab/2023_Moshkov_NatComm)]![GitHub stars](https://img.shields.io/github/stars/CaicedoLab/2023_Moshkov_NatComm.svg?logo=github&label=Stars)

### 2022

- <a name=""></a> **[Multimodal deep learning]** Pan-Cancer Integrative Histology-Genomic Analysis via Multimodal Deep Learning (**Cancer Cell**) [[paper](https://www.cell.com/cancer-cell/fulltext/S1535-6108(22)00317-8)] [[code](https://github.com/mahmoodlab/PORPOISE)]![GitHub stars](https://img.shields.io/github/stars/mahmoodlab/PORPOISE.svg?logo=github&label=Stars)

- <a name=""></a> **[Datasets and Benchmark]** High-dimensional gene expression and morphology profiles of cells across 28,000 genetic and chemical perturbations (**Nature Methods**) [[paper](https://www.nature.com/articles/s41592-022-01667-0)] [[code](https://github.com/carpenter-singh-lab/2022_Haghighi_NatureMethods)]![GitHub stars](https://img.shields.io/github/stars/carpenter-singh-lab/2022_Haghighi_NatureMethods.svg?logo=github&label=Stars)

- <a name=""></a> Morphology and gene expression profiling provide complementary information for mapping cell state (**Cell Systems**) [[paper](https://www.sciencedirect.com/science/article/pii/S2405471222004021)] [[code](https://github.com/broadinstitute/lincs-profiling-complementarity/tree/master)]![GitHub stars](https://img.shields.io/github/stars/broadinstitute/lincs-profiling-complementarity.svg?logo=github&label=Stars)

- <a name=""></a> Integrating cell morphology with gene expression and chemical structure to aid mitochondrial toxicity detection (**Communications Biology**) [[paper](https://www.nature.com/articles/s42003-022-03763-5)] [[code](https://github.com/srijitseal/Using-Cell-Morphology-Gene-Expression-Features-and-Structural-Fingerprints-to-Aid-Detection-of-Mito/)]![GitHub stars](https://img.shields.io/github/stars/srijitseal/Using-Cell-Morphology-Gene-Expression-Features-and-Structural-Fingerprints-to-Aid-Detection-of-Mito.svg?logo=github&label=Stars)

### 2021 and before

- <a name=""></a> **[Multimodal deep learning]** Capturing single-cell heterogeneity via data fusion improves image-based profiling (**Nature Communications**) [[paper](https://www.nature.com/articles/s41467-019-10154-8)] [[code](https://github.com/carpenterlab/2018_Rohban_NatComm)]![GitHub stars](https://img.shields.io/github/stars/carpenterlab/2018_Rohban_NatComm.svg?logo=github&label=Stars)

</details>


## Multi-channel_Image_Processing
<details>
<summary>Details</summary>

### 2024
- <a name=""></a>**[ChannelViT]** Channel Vision Transformer: An Image Is Worth C x 16 x 16 Words (**ICLR 2024**) [[paper](https://arxiv.org/abs/2309.16108)] [[code](https://github.com/insitro/ChannelViT)]![GitHub stars](https://img.shields.io/github/stars/insitro/ChannelViT.svg?logo=github&label=Stars)

- <a name=""></a>**[CHAMMI]** CHAMMI: A benchmark for channel-adaptive models in microscopy imaging (**NIPS 2024**) [[paper](https://arxiv.org/abs/2310.19224)] [[code](https://github.com/chaudatascience/channel_adaptive_models)]![GitHub stars](https://img.shields.io/github/stars/chaudatascience/channel_adaptive_models.svg?logo=github&label=Stars)

- <a name=""></a>**[DiChaViT]** Enhancing Feature Diversity Boosts Channel-Adaptive Vision Transformers
 (**ArxiV**) [[paper](https://arxiv.org/pdf/2405.16419)]

- <a name=""></a>**[ChAda-ViT]** ChAda-ViT : Channel Adaptive Attention for Joint Representation Learning of Heterogeneous Microscopy Images (**CVPR 2024**) [[paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Bourriez_ChAda-ViT__Channel_Adaptive_Attention_for_Joint_Representation_Learning_of_CVPR_2024_paper.pdf)] [[code](https://github.com/nicoboou/chadavit)]![GitHub stars](https://img.shields.io/github/stars/nicoboou/chadavit.svg?logo=github&label=Stars)

### 2023


### 2022

</details>


## Others
<details>
<summary>Details</summary>
- <a name=""></a>**[Checklists]** Community-developed checklists for publishing images and image analyses (**Nature Methods**) [[paper](https://www.nature.com/articles/s41592-023-01987-9)][[code](https://github.com/QUAREP-LiMi/WG12_checklists_for_image_publishing)]![GitHub stars](https://img.shields.io/github/stars/QUAREP-LiMi/WG12_checklists_for_image_publishing.svg?logo=github&label=Stars)








