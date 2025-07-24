# Awesome Phenotypic Drug Discovery (PDD)
```
在药物发现中，表型（Phenotypic） 通常指的是细胞或生物体在药物处理后所表现出的可观察特征或变化。这些变化可以包括细胞形态、基因表达、蛋白质水平和代谢产物等多种生物学响应。
在表型药物发现（Phenotypic Drug Discovery, PDD） 中，研究人员通过观察和分析这些表型变化来评估药物的效果和潜在的治疗机制。

In drug discovery, phenotypic typically refers to the observable characteristics or changes in cells or organisms after drug treatment. These changes can include various biological responses such as cell morphology, gene expression, protein levels, and metabolites.
In Phenotypic Drug Discovery (PDD), researchers evaluate the effects and potential therapeutic mechanisms of drugs by observing and analyzing these phenotypic changes.
```

## Papers

Considering the increasing number of papers in this field, we roughly summarize some articles and put them into the following categories:

* [Image-based PDD](#Image-based_PDD)
* [Gene-based PDD](#Gene-based_PDD)
* [Image & Gene-based PDD](#Image_Gene-based_PDD)
* [De Novo Drug/Molecule Design](#De_Novo_Drug_Design)
* [Multi-channel Image Processing](#Multi-channel_Image_Processing)


# Survey
- <a name=""></a>**[2024]** Cell Painting: a decade of discovery and innovation in cellular imaging (**Nature Methods**) [[paper](https://www.nature.com/articles/s41592-024-02528-8)]
- <a name=""></a>**[2024]** Morphological profiling for drug discovery in the era of deep learning (**Briefings in Bioinformatics**) [[paper](https://academic.oup.com/bib/article/25/4/bbae284/7693952)] [[中文解读](https://zhuanlan.zhihu.com/p/708163198?utm_campaign=shareopn&utm_medium=social&utm_psn=1822807077606780929&utm_source=wechat_session)] 
- <a name=""></a>**[2024]** Artificial intelligence for high content imaging in drug discovery (**Current Opinion in Structural Biology**) [[paper](https://www.sciencedirect.com/science/article/pii/S0959440X24000691)]
- <a name=""></a>**[2023]** Deep learning in image-based phenotypic drug discovery (**Trends in Cell Biology**) [[paper](https://www.cell.com/trends/cell-biology/abstract/S0962-8924(22)00262-8)]
- <a name=""></a>**[2022]** Phenotypic drug discovery: recent successes, lessons learned and new directions (**Nature Reviews Drug Discovery**) [[paper](https://www.nature.com/articles/s41573-022-00472-w)]
- <a name=""></a>**[2020]** Image-based profiling for drug discovery: due for a machine-learning upgrade? (**Nature Reviews Drug Discovery**) [[paper](https://www.nature.com/articles/s41573-020-00117-w)]


# Datasets
- <a name=""></a>**[Broad Cell Painting Gallery]** [[Link](https://registry.opendata.aws/cellpainting-gallery/)]  [[Datasets Overview](https://github.com/broadinstitute/cellpainting-gallery/blob/main/README.md)]  [[AWS Overview](https://open.quiltdata.com/b/cellpainting-gallery/tree/)] [[Bray Dataset](https://github.com/gigascience/paper-bray2017/tree/master)]
- <a name=""></a>**[Tahoe-100M]** [[Link](https://github.com/ArcInstitute/arc-virtual-cell-atlas/blob/main/tahoe-100M/README.md)] [[Paper](https://doi.org/10.1101/2025.02.20.639398)]
- <a name=""></a>**[Broad Bioimage Benchmark Collection]** [[Link](https://bbbc.broadinstitute.org/)] [[Paper](https://www.nature.com/articles/nmeth.2083)]
- <a name=""></a>**[Image Data Resource (IDR)]** [[Link](https://idr.openmicroscopy.org/)]
- <a name=""></a>**[NYSCF Automated Deep Phenotyping Dataset (ADPD)]** [[Link](https://nyscf.org/open-source/nyscf-adpd/)]
- <a name=""></a>**[RxRx from Recursion]** [[Link](https://www.rxrx.ai/datasets)]


# Tools

- <a name=""></a>**[PhenoProfiler]** PhenoProfiler: Advancing Morphology Representations for Image-based Drug Discovery (**Biorxiv**) [[paper](https://arxiv.org/abs/2502.19568)] [[code](https://github.com/QSong-github/PhenoProfiler)]![GitHub stars](https://img.shields.io/github/stars/QSong-github/PhenoProfiler.svg?logo=github&label=Stars) [Webserver](https://phenoprofiler.org/)
 
- <a name=""></a>**[DeepProfiler]** Learning representations for image-based profiling of perturbations (**Nature Communications**) [[paper](https://www.nature.com/articles/s41467-024-45999-1)] [[code](https://github.com/cytomining/DeepProfiler)]![GitHub stars](https://img.shields.io/github/stars/cytomining/DeepProfiler.svg?logo=github&label=Stars)
 
- <a name=""></a> **[Pycytominer]** Reproducible image-based profiling with Pycytominer (**Arxiv**) [[paper](https://arxiv.org/abs/2311.13417)] [[code](https://github.com/cytomining/pycytominer)]![GitHub stars](https://img.shields.io/github/stars/cytomining/pycytominer.svg?logo=github&label=Stars)
 
- <a name=""></a> **[SPACe]** SPACe: an open-source, single-cell analysis of Cell Painting data (**Nature Communications**) [[paper](https://www.nature.com/articles/s41467-024-54264-4)] [[code](https://github.com/dlabate/SPACe)]![GitHub stars](https://img.shields.io/github/stars/dlabate/SPACe.svg?logo=github&label=Stars)
 
- <a name=""></a> **[CellProfiler]** CellProfiler 3.0:Next-generation imageprocessing for biology (**PLOS BIOLOGY**) [[paper](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.2005970)] [[code](https://github.com/afermg/cp_measure)]![GitHub stars](https://img.shields.io/github/stars/afermg/cp_measure.svg?logo=github&label=Stars)

- <a name=""></a> **[cp_measure]** cp_measure: API-first feature extraction for image-based profiling workflows (**PMLR2025**) [[paper](https://arxiv.org/pdf/2507.01163)] [[code](https://github.com/afermg/cp_measure)]![GitHub stars](https://img.shields.io/github/stars/afermg/cp_measure.svg?logo=github&label=Stars)

<!--
- <a name=""></a> **[CellSAM]** CellSAM: A Foundation Model for Cell Segmentation (**Biorxiv**) [[paper](https://www.biorxiv.org/content/10.1101/2023.11.17.567630v3)] [[code](https://github.com/vanvalenlab/cellSAM)]![GitHub stars](https://img.shields.io/github/stars/vanvalenlab/cellSAM.svg?logo=github&label=Stars)
- <a name=""></a> **[Cellpose]** Cellpose: a generalist algorithm for cellular segmentation (**Nature Methods**) [[paper](https://www.nature.com/articles/s41592-020-01018-x)] [[code](https://github.com/mouseland/cellpose)]![GitHub stars](https://img.shields.io/github/stars/mouseland/cellpose.svg?logo=github&label=Stars)
-->

# Papers

## Image-based_PDD
<details open>
<summary>Details</summary>

### 2025


- <a name=""></a>**[MINER]** Multi-modal Contrastive Learning with Negative Sampling Calibration for Phenotypic Drug Discovery (**CVPR 2025**) [[paper](https://openaccess.thecvf.com//content/CVPR2025/papers/Rao_Multi-modal_Contrastive_Learning_with_Negative_Sampling_Calibration_for_Phenotypic_Drug_CVPR_2025_paper.pdf)][[code](https://github.com/biomed-AI/MINER)]![GitHub stars](https://img.shields.io/github/stars/biomed-AI/MINER.svg?logo=github&label=Stars)

- <a name=""></a>**[CellFlux]** CellFlux: Simulating Cellular Morphology Changes via Flow Matching (**ICML 2025**) [[paper](https://arxiv.org/pdf/2502.09775)] [[code](https://github.com/yuhui-zh15/CellFlux)]![GitHub stars](https://img.shields.io/github/stars/yuhui-zh15/CellFlux.svg?logo=github&label=Stars)

 - <a name=""></a>**[IMPA]** Predicting cell morphological responses to perturbations using generative modeling (**Nature Communications 2025**) [[paper](https://www.nature.com/articles/s41467-024-55707-8)] [[code](https://github.com/theislab/IMPA)]![GitHub stars](https://img.shields.io/github/stars/theislab/IMPA.svg?logo=github&label=Stars)
 
- <a name=""></a>**[MorphoDiff]** MorphoDiff: Cellular Morphology Painting with Diffusion Models (**ICLR 2025**) [[paper](https://openreview.net/pdf?id=PstM8YfhvI)] [[code](https://github.com/bowang-lab/MorphoDiff)]![GitHub stars](https://img.shields.io/github/stars/bowang-lab/MorphoDiff.svg?logo=github&label=Stars)



### 2024

- <a name=""></a>**[Foundation model]** Confounder-aware foundation modeling for accurate phenotype profiling in cell imaging (**BioRxiv**) [[paper](https://www.biorxiv.org/content/10.1101/2024.12.23.630105v1#:~:text=To%20address%20this%2C%20we%20present%20a%20confounder-aware%20foundation,generation%20of%20balanced%20synthetic%20datasets%20for%20robust%20bio)]


- <a name=""></a>**[PhenoScreen]** PhenoScreen: A Dual-Space Contrastive Learning Framework-based Phenotypic Screening Method by Linking Chemical Perturbations to Cellular Morphology (**BioRxiv**) [[paper](https://www.biorxiv.org/content/10.1101/2024.10.23.619752v1)] [[code](https://github.com/Shihang-Wang-58/PhenoScreen)]![GitHub stars](https://img.shields.io/github/stars/Shihang-Wang-58/PhenoScreen.svg?logo=github&label=Stars)

- <a name=""></a>**[Batch Correction]** Evaluating batch correction methods for image-based cell profiling (**Nature Communications**) [[paper](https://www.nature.com/articles/s41467-024-50613-5)] [[code](https://github.com/carpenter-singh-lab/2023_Arevalo_BatchCorrection)]![GitHub stars](https://img.shields.io/github/stars/carpenter-singh-lab/2023_Arevalo_BatchCorrection.svg?logo=github&label=Stars)

- <a name=""></a>**[scDINO]** Self-supervised vision transformers accurately decode cellular state heterogeneity (**BioRxiv**) [[paper](https://www.biorxiv.org/content/10.1101/2023.01.16.524226v1)][[code](https://github.com/JacobHanimann/scDINO)]![GitHub stars](https://img.shields.io/github/stars/JacobHanimann/scDINO.svg?logo=github&label=Stars)

- <a name=""></a>**[MIGA]** Cross-Modal Graph Contrastive Learning with Cellular Images (**Advanced science**) [[paper](https://onlinelibrary.wiley.com/doi/full/10.1002/advs.202404845)] [[code](https://github.com/prokia/MIGA)]![GitHub stars](https://img.shields.io/github/stars/prokia/MIGA.svg?logo=github&label=Stars)


### 2023

- <a name=""></a> Deep representation learning determines drug mechanism of action from cell painting images (**Digital Discovery**) [[paper](https://pubs.rsc.org/en/content/articlelanding/2023/dd/d3dd00060e)] [[code](https://github.com/pfizer-opensource/moa-profiler)]![GitHub stars](https://img.shields.io/github/stars/pfizer-opensource/moa-profiler.svg?logo=github&label=Stars)

- <a name=""></a>**[CLOOME(NC)]** CLOOME: contrastive learning unlocks bioimaging databases for queries with chemical structures (**Nature Communications**) [[paper](https://www.nature.com/articles/s41467-023-42328-w)] [[code](https://github.com/ml-jku/cloome)]![GitHub stars](https://img.shields.io/github/stars/ml-jku/cloome.svg?logo=github&label=Stars)

### 2022

- <a name=""></a> **[Dataset]** Integrating deep learning and unbiased automated high-content screening to identify complex disease signatures in human fibroblasts (**Nature Communications**) [[paper](https://www.nature.com/articles/s41467-022-28423-4)] [[dataset](https://nyscf.org/open-source/nyscf-adpd/)]

- <a name=""></a> **[WS-DINO]** Self-Supervised Learning of Phenotypic Representations from Cell Images with Weak Labels (**LMRL @NeurIPS 2022**) [[paper](https://arxiv.org/abs/2209.07819)] [[code](https://github.com/crosszamirski/WS-DINO/)]![GitHub stars](https://img.shields.io/github/stars/crosszamirski/WS-DINO.svg?logo=github&label=Stars)

- <a name=""></a> **[CLOOME]** Contrastive learning of image- and structure-based representations in drug discovery (**MLDD @ICLR 2022**) [[paper](https://openreview.net/pdf?id=OdXKRtg1OG)] [[code](https://github.com/ml-jku/cloome)]![GitHub stars](https://img.shields.io/github/stars/ml-jku/cloome.svg?logo=github&label=Stars) [[文章解读](https://zhuanlan.zhihu.com/p/524470856)] 

</details>

## Gene-based_PDD
<details open>
<summary>Details</summary>

### 2025

- <a name=""></a>**[CellFM]** CellFM: a large-scale foundation model pre-trained on transcriptomics of 100 million human cells (**Nature Communications**) [[paper](https://www.nature.com/articles/s41467-025-59926-5)] [[code](https://github.com/biomed-AI/CellFM)]![GitHub stars](https://img.shields.io/github/stars/biomed-AI/CellFM.svg?logo=github&label=Stars)


### 2024

- <a name=""></a>**[GEARS]** Predicting transcriptional outcomes of novel multigene perturbations with GEARS (**Nature Biotechnology**) [[paper](https://www.nature.com/articles/s41587-023-01905-6)] [[code](https://github.com/snap-stanford/GEARS)]![GitHub stars](https://img.shields.io/github/stars/snap-stanford/GEARS.svg?logo=github&label=Stars)
 
- <a name=""></a>**[TranSiGen]** Deep representation learning of chemical-induced transcriptional profile for phenotype-based drug discovery (**Nature Communications**) [[paper](https://www.nature.com/articles/s41467-024-49620-3)] [[code](https://github.com/myzhengSIMM/TranSiGen)]![GitHub stars](https://img.shields.io/github/stars/myzhengSIMM/TranSiGen.svg?logo=github&label=Stars)

- <a name=""></a>**[PRnet]** Predicting transcriptional responses to novel chemical perturbations using deep generative model for drug discovery (**Nature Communications**) [[paper](https://www.nature.com/articles/s41467-024-53457-1)] [[code](https://github.com/Perturbation-Response-Prediction/PRnet)]![GitHub stars](https://img.shields.io/github/stars/Perturbation-Response-Prediction/PRnet.svg?logo=github&label=Stars)

- <a name=""></a>**[PertKGE]** Identifying compound-protein interactions with knowledge graph embedding of perturbation transcriptomics (**Cell Genomics**) [[paper](https://www.sciencedirect.com/science/article/pii/S2666979X24002660?via%3Dihub#sec4)] [[code](https://github.com/myzhengSIMM/PertKGE)]![GitHub stars](https://img.shields.io/github/stars/myzhengSIMM/PertKGE.svg?logo=github&label=Stars)

- <a name=""></a> An interpretable deep learning framework for genome-informed precision oncology (**Nature Machine Intelligence**) [[paper](https://www.nature.com/articles/s42256-024-00866-y)] [[code](https://github.com/myzhengSIMM/PertKGE)]![GitHub stars](https://img.shields.io/github/stars/myzhengSIMM/PertKGE.svg?logo=github&label=Stars)

- <a name=""></a>**[PERCEPTION]** PERCEPTION predicts patient response and resistance to treatment using single-cell transcriptomics of their tumors (**Nature Cancer**) [[paper](https://www.nature.com/articles/s43018-024-00756-7)] [[code](https://github.com/ruppinlab/PERCEPTION)]![GitHub stars](https://img.shields.io/github/stars/ruppinlab/PERCEPTION.svg?logo=github&label=Stars)


### 2023


- <a name=""></a>**[SCAD]** Enabling Single-Cell Drug Response Annotations from Bulk RNA-Seq Using SCAD (**Advanced Science**) [[paper](https://onlinelibrary.wiley.com/doi/10.1002/advs.202204113)] [[code](https://github.com/CompBioT/SCAD)]![GitHub stars](https://img.shields.io/github/stars/CompBioT/SCAD.svg?logo=github&label=Stars)

- <a name=""></a>**[ASGARD]** ASGARD is A Single-cell Guided Pipeline to Aid Repurposing of Drugs (**Nature Communications**) [[paper](https://www.nature.com/articles/s41467-023-36637-3)] [[code](https://github.com/lanagarmire/ASGARD)]![GitHub stars](https://img.shields.io/github/stars/lanagarmire/ASGARD.svg?logo=github&label=Stars)

### 2022

- <a name=""></a>**[scDEAL]** Deep transfer learning of cancer drug responses by integrating bulk and single-cell RNA-seq data (**Nature Communications**) [[paper](https://www.nature.com/articles/s41467-022-34277-7)] [[code](https://github.com/OSU-BMBL/scDEAL)]![GitHub stars](https://img.shields.io/github/stars/OSU-BMBL/scDEAL.svg?logo=github&label=Stars)

- <a name=""></a>**[chemCPA]** Predicting Cellular Responses to Novel Drug Perturbations at a Single-Cell Resolution (**NIPS 2022**) [[paper](https://neurips.cc/virtual/2022/poster/53227)] [[code](https://github.com/theislab/chemCPA)]![GitHub stars](https://img.shields.io/github/stars/theislab/chemCPA.svg?logo=github&label=Stars)

### 2021
- <a name=""></a>**[Velodrome]** Out-of-distribution generalization from labelled and unlabelled gene expression data for drug response prediction (**Nature Machine Intelligence**) [[paper](https://www.nature.com/articles/s42256-021-00408-w)] [[code](https://github.com/hosseinshn/Velodrome)]![GitHub stars](https://img.shields.io/github/stars/hosseinshn/Velodrome.svg?logo=github&label=Stars)

- <a name=""></a>**[PathDSP]** Explainable drug sensitivity prediction through cancer pathway enrichment (**Scientific reports**) [[paper](https://www.nature.com/articles/s41598-021-82612-7?fromPaywallRec=false)] [[code](https://github.com/TangYiChing/PathDSP)]![GitHub stars](https://img.shields.io/github/stars/TangYiChing/PathDSP.svg?logo=github&label=Stars)

- <a name=""></a>**[VAEN]** Deep generative neural network for accurate drug response imputatio (**Nature Communications**) [[paper](https://www.nature.com/articles/s41467-021-21997-5)] [[code](https://github.com/bsml320/VAEN/)]![GitHub stars](https://img.shields.io/github/stars/bsml320/VAEN.svg?logo=github&label=Stars)


</details>

## Image_Gene-based_PDD
<details open>
<summary>Details</summary>

- <a name=""></a>**[InfoAlign]** Learning Molecular Representation in a Cell (**ICLR 2025**) [[paper](https://openreview.net/forum?id=BbZy8nI1si)] [[code](https://github.com/liugangcode/InfoAlign)]![GitHub stars](https://img.shields.io/github/stars/liugangcode/InfoAlign.svg?logo=github&label=Stars)

### 2024

- <a name=""></a>**[Datasets]** JUMP Cell Painting dataset: morphological impact of 136,000 chemical and genetic perturbations (**Arxiv**) [[paper](https://www.biorxiv.org/content/10.1101/2023.03.23.534023v2)] [[dataset](https://registry.opendata.aws/cellpainting-gallery/)]


- <a name=""></a> Cell morphological representations of genes enhance prediction of drug targets (**Biorxiv**) [[paper](https://www.biorxiv.org/content/biorxiv/early/2024/06/10/2024.06.08.598076.full.pdf)]

 
- <a name=""></a>**[Datasets and Benchmark]** Three million images and morphological profiles of cells treated with matched chemical and genetic perturbations (**Nature Methods**) [[paper](https://www.nature.com/articles/s41592-024-02241-6)] [[code](https://github.com/jump-cellpainting/2024_Chandrasekaran_NatureMethods/tree/main)]![GitHub stars](https://img.shields.io/github/stars/jump-cellpainting/2024_Chandrasekaran_NatureMethods.svg?logo=github&label=Stars)

- <a name=""></a>**[cmQTL]** High-dimensional phenotyping to define the genetic basis of cellular morphology (**Nature Communications**) [[paper](https://www.nature.com/articles/s41467-023-44045-w)] [[code](https://github.com/broadinstitute/cmQTL)]![GitHub stars](https://img.shields.io/github/stars/broadinstitute/cmQTL.svg?logo=github&label=Stars)


### 2023
 
- <a name=""></a>**[InfoCORE]** Removing Biases from Molecular Representations via Information Maximization (**ICLR**) [[paper](https://arxiv.org/abs/2312.00718)] [[code](https://github.com/uhlerlab/InfoCORE)]![GitHub stars](https://img.shields.io/github/stars/uhlerlab/InfoCORE.svg?logo=github&label=Stars)

- <a name=""></a> Predicting compound activity from phenotypic profiles and chemical structures (**Nature Communications**) [[paper](https://www.nature.com/articles/s41467-023-37570-1)] [[code](https://github.com/CaicedoLab/2023_Moshkov_NatComm)]![GitHub stars](https://img.shields.io/github/stars/CaicedoLab/2023_Moshkov_NatComm.svg?logo=github&label=Stars)

### 2022

- <a name=""></a> **[Multimodal deep learning]** Pan-Cancer Integrative Histology-Genomic Analysis via Multimodal Deep Learning (**Cancer Cell**) [[paper](https://www.cell.com/cancer-cell/fulltext/S1535-6108(22)00317-8)] [[code](https://github.com/mahmoodlab/PORPOISE)]![GitHub stars](https://img.shields.io/github/stars/mahmoodlab/PORPOISE.svg?logo=github&label=Stars)

- <a name=""></a> **[Datasets and Benchmark]** High-dimensional gene expression and morphology profiles of cells across 28,000 genetic and chemical perturbations (**Nature Methods**) [[paper](https://www.nature.com/articles/s41592-022-01667-0)] [[code](https://github.com/carpenter-singh-lab/2022_Haghighi_NatureMethods)]![GitHub stars](https://img.shields.io/github/stars/carpenter-singh-lab/2022_Haghighi_NatureMethods.svg?logo=github&label=Stars)

- <a name=""></a> Morphology and gene expression profiling provide complementary information for mapping cell state (**Cell Systems**) [[paper](https://www.sciencedirect.com/science/article/pii/S2405471222004021)] [[code](https://github.com/broadinstitute/lincs-profiling-complementarity/tree/master)]![GitHub stars](https://img.shields.io/github/stars/broadinstitute/lincs-profiling-complementarity.svg?logo=github&label=Stars)

- <a name=""></a> Integrating cell morphology with gene expression and chemical structure to aid mitochondrial toxicity detection (**Communications Biology**) [[paper](https://www.nature.com/articles/s42003-022-03763-5)] [[code](https://github.com/srijitseal/Using-Cell-Morphology-Gene-Expression-Features-and-Structural-Fingerprints-to-Aid-Detection-of-Mito/)]![GitHub stars](https://img.shields.io/github/stars/srijitseal/Using-Cell-Morphology-Gene-Expression-Features-and-Structural-Fingerprints-to-Aid-Detection-of-Mito.svg?logo=github&label=Stars)

### 2021 and before

- <a name=""></a> **[Multimodal deep learning]** Capturing single-cell heterogeneity via data fusion improves image-based profiling (**Nature Communications**) [[paper](https://www.nature.com/articles/s41467-019-10154-8)] [[code](https://github.com/carpenterlab/2018_Rohban_NatComm)]![GitHub stars](https://img.shields.io/github/stars/carpenterlab/2018_Rohban_NatComm.svg?logo=github&label=Stars)

</details>



## De_Novo_Drug_Design
<details open>
<summary>Details</summary>

### 2025

- <a name=""></a>**[SketchMol]** Image-based generation for molecule design with SketchMol (**Nature Machine Intelligence**) [[paper](https://www.nature.com/articles/s42256-025-00982-3)][[code](https://github.com/WangZiXubiubiu/SketchMol-v1)]![GitHub stars](https://img.shields.io/github/stars/WangZiXubiubiu/SketchMol-v1.svg?logo=github&label=Stars)


### 2024

- <a name=""></a>**[GeminiMol]** Conformational Space Profiling Enhances Generic Molecular Representation for AI-Powered Ligand-Based Drug Discovery (**Advanced Science**) [[paper](https://advanced.onlinelibrary.wiley.com/doi/10.1002/advs.202403998)] [[code](https://github.com/Wang-Lin-boop/GeminiMol)]![GitHub stars](https://img.shields.io/github/stars/Wang-Lin-boop/GeminiMol.svg?logo=github&label=Stars)

- <a name=""></a>**[GFlowNets]** Cell Morphology-Guided Small Molecule Generation with GFlowNets (**ICML 2024**) [[paper](https://arxiv.org/abs/2408.05196)]

- <a name=""></a>**[Survey]** From Intuition to AI: Evolution of Small Molecule Representations in Drug Discovery (**BIB**) [[paper](https://academic.oup.com/bib/article/25/1/bbad422/7455245)]

- <a name=""></a>**[Survey]** A survey of generative AI for de novo drug design: new frontiers in molecule and protein generation (**BIB**) [[paper](https://academic.oup.com/bib/article/25/4/bbae338/7713723)][[code](https://github.com/gersteinlab/GenAI4Drug)]![GitHub stars](https://img.shields.io/github/stars/gersteinlab/GenAI4Drug.svg?logo=github&label=Stars)

- <a name=""></a>**[TransGEM]** TransGEM: a molecule generation model based on Transformer with gene expression data (**BIB**) [[paper](https://academic.oup.com/bioinformatics/article/40/5/btae189/7649318)] [[code](https://github.com/hzauzqy/TransGEM)]![GitHub stars](https://img.shields.io/github/stars/hzauzqy/TransGEM.svg?logo=github&label=Stars)

- <a name=""></a>**[Gx2Mol]** Gx2Mol: De Novo Generation of Hit-like Molecules from Gene Expression Profiles via Deep Learning (**BioRxiv**) [[paper](https://arxiv.org/abs/2412.19422)] [[code](https://github.com/naruto7283/Gx2Mol)]![GitHub stars](https://img.shields.io/github/stars/naruto7283/Gx2Mol.svg?logo=github&label=Stars)

- <a name=""></a>**[CPMolGAN]** Cell morphology-guided de novo hit design by conditioning GANs on phenotypic image features (**Digital Discovery**) [[paper](https://pubs.rsc.org/en/content/articlelanding/2023/dd/d2dd00081d)] [[code](https://github.com/Bayer-Group/CPMolGAN)]![GitHub stars](https://img.shields.io/github/stars/Bayer-Group/CPMolGAN.svg?logo=github&label=Stars)

- <a name=""></a>**[GexMolGen]** GexMolGen: cross-modal generation of hit-like molecules via large language model encoding of gene expression signatures (**BIB**) [[paper](https://academic.oup.com/bib/article/25/6/bbae525/7845937)] [[code](https://github.com/Bunnybeibei/GexMolGen)]![GitHub stars](https://img.shields.io/github/stars/Bunnybeibei/GexMolGen.svg?logo=github&label=Stars)

- <a name=""></a>**[Gex2SGen]** Gex2SGen: Designing Drug-like Molecules from Desired Gene Expression Signatures (**Journal of Chemical Information and Modeling**) [[paper](https://pubs.acs.org/doi/10.1021/acs.jcim.2c01301?ref=pdf)]

- <a name=""></a>**[Survey]** Diffusion Models in De Novo Drug Design (**Journal of Chemical Information and Modeling**) [[paper](https://pubs.acs.org/doi/10.1021/acs.jcim.4c01107)]


### 2023

- <a name=""></a>**[KPGT]** A Knowledge-Guided Pre-training Framework for Improving Molecular Representation Learning (**nature communications**) [[paper](https://www.nature.com/articles/s41467-023-43214-1)][[code](https://github.com/lihan97/KPGT)]![GitHub stars](https://img.shields.io/github/stars/lihan97/KPGT.svg?logo=github&label=Stars)

- <a name=""></a>**[Survey]** Graph neural networks for conditional de novo drug design (**Wiley Interdisciplinary Reviews: Computational Molecular Science**) [[paper](https://wires.onlinelibrary.wiley.com/doi/pdfdirect/10.1002/wcms.1651)]





</details>





## Multi-channel_Image_Processing
<details open>
<summary>Details</summary>

### 2024

- <a name=""></a>**[CA-MAE]** Masked Autoencoders for Microscopy are Scalable Learners of Cellular Biology (**CVPR 2024**) [[paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Kraus_Masked_Autoencoders_for_Microscopy_are_Scalable_Learners_of_Cellular_Biology_CVPR_2024_paper.pdf)] [[code](https://github.com/recursionpharma/maes_microscopy)]![GitHub stars](https://img.shields.io/github/stars/recursionpharma/maes_microscopy.svg?logo=github&label=Stars)

- <a name=""></a>**[ChannelViT]** Channel Vision Transformer: An Image Is Worth C x 16 x 16 Words (**ICLR 2024**) [[paper](https://arxiv.org/abs/2309.16108)] [[code](https://github.com/insitro/ChannelViT)]![GitHub stars](https://img.shields.io/github/stars/insitro/ChannelViT.svg?logo=github&label=Stars)

- <a name=""></a>**[CHAMMI]** CHAMMI: A benchmark for channel-adaptive models in microscopy imaging (**NIPS 2024**) [[paper](https://arxiv.org/abs/2310.19224)] [[code](https://github.com/chaudatascience/channel_adaptive_models)]![GitHub stars](https://img.shields.io/github/stars/chaudatascience/channel_adaptive_models.svg?logo=github&label=Stars)

- <a name=""></a>**[DiChaViT]** Enhancing Feature Diversity Boosts Channel-Adaptive Vision Transformers
 (**ArxiV**) [[paper](https://arxiv.org/pdf/2405.16419)]

- <a name=""></a>**[ChAda-ViT]** ChAda-ViT : Channel Adaptive Attention for Joint Representation Learning of Heterogeneous Microscopy Images (**CVPR 2024**) [[paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Bourriez_ChAda-ViT__Channel_Adaptive_Attention_for_Joint_Representation_Learning_of_CVPR_2024_paper.pdf)] [[code](https://github.com/nicoboou/chadavit)]![GitHub stars](https://img.shields.io/github/stars/nicoboou/chadavit.svg?logo=github&label=Stars)


</details>


## Others
<details open>
<summary>Details</summary>

- <a name=""></a>**[Checklists]** Community-developed checklists for publishing images and image analyses (**Nature Methods**) [[paper](https://www.nature.com/articles/s41592-023-01987-9)][[code](https://github.com/QUAREP-LiMi/WG12_checklists_for_image_publishing)]![GitHub stars](https://img.shields.io/github/stars/QUAREP-LiMi/WG12_checklists_for_image_publishing.svg?logo=github&label=Stars)




Any form of communication and co-operation is welcome [Email:yc47955@um.edu.mo](yc47955@um.edu.mo).




