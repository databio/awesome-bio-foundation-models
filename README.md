# Awesome bio foundation models

A collection of large-scale pretrained models built specifically for biological data.

## DNA and genome language models

- [AgroNT](https://huggingface.co/InstaDeepAI/agro-nucleotide-transformer-1b): nucleotide transformer trained on edible plant genomes
- [Caduceus](https://github.com/kuleshov-group/caduceus): bi-directional, reverse-complement-equivariant long-range DNA model
- [DNABERT](https://github.com/jerryji1993/DNABERT): first BERT-style pretrained model of the human genome
- [DNABERT-2](https://github.com/MAGICS-LAB/DNABERT_2): efficient multi-species genome model with byte-pair tokenization
- [DNABERT-S](https://github.com/MAGICS-LAB/DNABERT_S): species-aware embeddings for genome discrimination
- [Evo](https://github.com/evo-design/evo): genome-scale generative model spanning molecular to genome scale
- [Evo 2](https://github.com/ArcInstitute/evo2): genome modeling and design across all domains of life
- [GENA-LM](https://github.com/AIRI-Institute/GENA_LM): open-source foundation models trained on human genome sequences using byte-pair encoding
- [GenSLMs](https://github.com/ramanathanlab/genslm): genome-scale language models trained on microbial genomes
- [gLM2](https://github.com/TattaBio/gLM2): mixed-modality genomic language model over the OMG corpus
- [GPN](https://github.com/songlab-cal/gpn): genomic pretrained network, including the multiple-alignment GPN-MSA variant
- [GROVER](https://huggingface.co/PoetschLab/GROVER): DNA language model learning sequence context in the human genome
- [HyenaDNA](https://github.com/HazyResearch/hyena-dna): long-range genomic sequence modeling at single-nucleotide resolution
- [megaDNA](https://github.com/lingxusb/megaDNA): long-context generative model of bacteriophage genomes
- [Nucleotide Transformer](https://github.com/instadeepai/nucleotide-transformer): multi-species foundation models for genomics

## Regulatory genome models

- [AlphaGenome](https://github.com/google-deepmind/alphagenome): multi-modal regulatory prediction across megabase contexts
- [Borzoi](https://github.com/calico/borzoi): RNA-seq coverage prediction from sequence
- [Enformer](https://github.com/google-deepmind/deepmind-research/tree/master/enformer): long-range transformer for gene expression prediction
- [Sei](https://github.com/FunctionLab/sei-framework): genome-wide model of regulatory sequence activity classes

## Single-cell transcriptome models

- [CellPLM](https://github.com/OmicsML/CellPLM): pretrained cell language model that treats cells as tokens
- [Geneformer](https://huggingface.co/ctheodoris/Geneformer): transfer-learning model pretrained on ~30 million single-cell transcriptomes
- [Nicheformer](https://github.com/theislab/nicheformer): foundation model spanning dissociated and spatial single-cell data
- [scBERT](https://github.com/TencentAILabHealthcare/scBERT): pretrained model for cell type annotation
- [scFoundation](https://github.com/biomap-research/scFoundation): large-scale model over the full transcriptome
- [scGPT](https://github.com/bowang-lab/scGPT): generative pretrained model for single-cell multi-omics
- [SCimilarity](https://github.com/Genentech/scimilarity): single-cell foundation model for cell annotation and similarity search
- [scMulan](https://github.com/SuperBianC/scMulan): multitask generative model of cell language
- [scPRINT](https://github.com/cantinilab/scPRINT): pretrained model for gene network inference and denoising
- [STATE](https://github.com/ArcInstitute/state): model of cellular perturbation response
- [UCE](https://github.com/snap-stanford/UCE): universal cell embeddings across species without cell-type labels

## Single-cell epigenome and chromatin models

- [Atacformer](https://doi.org/10.1101/2025.11.03.685753): transformer foundation model pretrained on 1.2 million scATAC-seq cells using genomic interval tokens
- [ChromFound](https://github.com/SAIS-LifeScience/ChromFound): genome-wide foundation model for single-cell chromatin accessibility
- [EpiAgent](https://github.com/xy-chen16/EpiAgent): foundation model for single-cell epigenomics
- [EpiFoundation](https://github.com/UCSC-VLAA/EpiFoundation): foundation model for single-cell ATAC-seq
- [geniml](https://github.com/databio/geniml): machine learning toolkit for genomic intervals, including region embeddings and tokenizers
- [scBasset](https://github.com/calico/scBasset): sequence-based model of single-cell accessibility

## RNA models

- [Orthrus](https://github.com/bowang-lab/Orthrus): contrastive mature RNA model for functional property prediction
- [RhoFold](https://github.com/ml4bio/RhoFold): language-model-based RNA 3D structure prediction
- [RiNALMo](https://github.com/lbcb-sci/RiNALMo): large RNA language model generalizing across structural tasks
- [RNAErnie](https://github.com/CatIIIIIIII/RNAErnie): motif-aware multi-purpose RNA language model
- [RNA-FM](https://github.com/ml4bio/RNA-FM): foundation model trained on non-coding RNA sequences
- [UTR-LM](https://github.com/a96123155/UTR-LM): language model of 5' UTRs for translation prediction

## Protein language models

- [Ankh](https://github.com/agemagician/Ankh): optimized general-purpose protein language model
- [ESM](https://github.com/facebookresearch/esm): ESM-1b, ESM-2, and ESMFold protein language models
- [ESM3 / ESM C](https://github.com/evolutionaryscale/esm): multimodal generative protein models over sequence, structure, and function
- [ProGen](https://github.com/salesforce/progen): generative protein language models for controllable design
- [ProtGPT2](https://huggingface.co/nferruz/ProtGPT2): autoregressive model generating de novo protein sequences
- [ProtTrans](https://github.com/agemagician/ProtTrans): transformer models trained on large protein corpora
- [SaProt](https://github.com/westlake-repl/SaProt): structure-aware protein language model

## Protein structure and design models

- [AlphaFold](https://github.com/google-deepmind/alphafold): highly accurate protein structure prediction
- [AlphaFold 3](https://github.com/google-deepmind/alphafold3): joint structure prediction for proteins, nucleic acids, and ligands
- [Boltz](https://github.com/jwohlwend/boltz): open biomolecular structure prediction model
- [Chai-1](https://github.com/chaidiscovery/chai-lab): multimodal model for molecular structure prediction
- [OpenFold](https://github.com/aqlaboratory/openfold): trainable open-source reimplementation of AlphaFold 2
- [ProteinMPNN](https://github.com/dauparas/ProteinMPNN): deep learning based protein sequence design
- [RFdiffusion](https://github.com/RosettaCommons/RFdiffusion): diffusion model for de novo protein design
- [RoseTTAFold All-Atom](https://github.com/baker-laboratory/RoseTTAFold-All-Atom): all-atom structure prediction for biomolecular assemblies

## Pathology and imaging models

- [CONCH](https://github.com/mahmoodlab/CONCH): vision-language foundation model for computational pathology
- [Prov-GigaPath](https://github.com/prov-gigapath/prov-gigapath): whole-slide foundation model for digital pathology
- [UNI](https://github.com/mahmoodlab/UNI): general-purpose pathology image encoder
- [Virchow](https://huggingface.co/paige-ai/Virchow): large pathology foundation model

## Biomedical text and knowledge models

- [BioBERT](https://github.com/dmis-lab/biobert): domain-specific language model pretrained on PubMed biomedical literature
- [BioGPT](https://github.com/microsoft/BioGPT): generative pretrained transformer for biomedical text
- [TxGNN](https://github.com/mims-harvard/TxGNN): zero-shot drug repurposing over a medical knowledge graph

## Benchmarks and evaluation

- [BEND](https://github.com/frederikkemarin/BEND): benchmark of DNA language models on realistic genomic tasks
- [DART-Eval](https://github.com/kundajelab/DART-Eval): benchmark of DNA models on regulatory sequence tasks
- [Genomic Benchmarks](https://github.com/ML-Bioinfo-CEITEC/genomic_benchmarks): datasets and baselines for genomic sequence classification
- [Open Problems](https://github.com/openproblems-bio/openproblems): living benchmarks for single-cell analysis tasks
- [ProteinGym](https://github.com/OATML-Markslab/ProteinGym): large-scale benchmark of protein fitness prediction and design
- [scEval](https://github.com/HelloWorldLTY/scEval): evaluation framework for single-cell foundation models

## Frameworks and model hubs

- [AIDO](https://github.com/genbio-ai/AIDO): modular system of foundation models across biological modalities
- [gReLU](https://github.com/Genentech/gReLU): framework for training, interpreting, and designing with sequence models
- [helical](https://github.com/helicalAI/helical): unified API for running bio foundation models
- [Kipoi](https://github.com/kipoi/kipoi): model zoo and standardized API for genomics models
- [scvi-tools](https://github.com/scverse/scvi-tools): probabilistic models and infrastructure for single-cell omics

## Reviews

- [Foundation models in bioinformatics](https://doi.org/10.1093/nsr/nwaf028)
- [Progress and opportunities of foundation models in bioinformatics](https://doi.org/10.1093/bib/bbae548)
- [Genomic language models: opportunities and challenges](https://doi.org/10.1016/j.tig.2024.11.013)
- [A comprehensive survey of genome language models in bioinformatics](https://doi.org/10.1093/bib/bbaf724)
- [The DNA dialect: a comprehensive guide to pretrained genomic language models](https://doi.org/10.1038/s44320-025-00184-4)
- [Benchmarking DNA foundation models for genomic and genetic tasks](https://doi.org/10.1038/s41467-025-65823-8)
- [Single-cell foundation models: bringing artificial intelligence into cell biology](https://doi.org/10.1038/s12276-025-01547-5)
- [A survey on foundation language models for single-cell biology](https://doi.org/10.18653/v1/2025.acl-long.26)
