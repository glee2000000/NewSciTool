---
title: Recent Usage & Benchmarks
---

# Verified Recent-Usage & Benchmark Anchors

[← Back to home](index.html)

For each tool, a 2025–2026 paper confirming it is still in active use, plus its dominant benchmark or agent-framework association. **Only rows the source research marked "Verified" are included.** Rows marked UNSURE or UNKNOWN in the original sweep — including Chai-1, ESM-3's newest third-party usage, DESeq2, CellTypist's AnnoAgent link, MatterGen, JARVIS-DFT, NOMAD, Chemprop, Uni-Mol, CREST, GROMACS, Quantum ESPRESSO, and VASP — are omitted here rather than presented as confirmed. Where a row mixed a verified tool-paper citation with an unconfirmed "newest usage" claim (ESM-3, CellTypist), only the verified citation is kept.

Two catalog papers anchor most of the framework column at once: **ChemCrow** (18 tools) and **Biomni** (105 software tools + 150 biological tools + 59 databases) — see [Agent Frameworks](agent-frameworks.html) for their full citations.

## Structure prediction & protein design

| Tool | Recent-usage anchor | Benchmark / Framework |
|---|---|---|
| AlphaFold3 | Peng, Ni, Liu, Hu, Zheng, "A comprehensive benchmarking of AlphaFold3 for predicting biomacromolecules and their interactions," *Briefings in Bioinformatics*, Nov 2025, DOI [10.1093/bib/bbaf616](https://doi.org/10.1093/bib/bbaf616) | Subject of AF3-family benchmarks; exercised inside Biomni |
| AlphaFold2 | Hýsková, Maršálková, Šimeček, "Balancing speed and precision in protein folding: AlphaFold2, ESMFold, OmegaFold," *Front. Genet.*, Jan 2026, DOI [10.3389/fgene.2025.1715037](https://doi.org/10.3389/fgene.2025.1715037) | Same benchmark; feeds ColabFold/RFdiffusion pipelines |
| ColabFold | Kallenborn et al., "GPU-accelerated homology search with MMseqs2," *Nature Methods*, Oct 2025, DOI [10.1038/s41592-025-02819-8](https://doi.org/10.1038/s41592-025-02819-8) | MSA backend for AlphaFold benchmarking |
| Boltz-2 | Wan et al., "On the Reliability of AI Methods in Drug Discovery: Evaluation of Boltz-2," arXiv, Mar 2026, [arXiv:2603.05532](https://arxiv.org/abs/2603.05532) | Used by the ToolMol agentic drug-discovery framework |
| ESM-3 | Hayes et al., "Simulating 500 million years of evolution with a language model," *Science*, 2025, DOI [10.1126/science.ads0018](https://doi.org/10.1126/science.ads0018) | Compared in Chai-1/structure benchmarks |
| RFdiffusion | Sappington et al., "Improved protein binder design using β-pairing targeted RFdiffusion," *Nat. Commun.*, 2026, DOI [10.1038/s41467-025-67866-3](https://doi.org/10.1038/s41467-025-67866-3) | Used in agentic biologics-design frameworks |
| ProteinMPNN | Same β-pairing RFdiffusion paper (ProteinMPNN for sequence design), *Nat. Commun.* 2026, DOI [10.1038/s41467-025-67866-3](https://doi.org/10.1038/s41467-025-67866-3) | Standard sequence-design step in RFdiffusion pipelines |
| Foldseek | Ghaly et al., "EcoFoldDB: Protein Structure-Guided Functional Profiling," *Environmental Microbiology*, 2025, DOI [10.1111/1462-2920.70178](https://doi.org/10.1111/1462-2920.70178) | SCOPe40 structure-search benchmark |
| MMseqs2 | Kallenborn et al., "GPU-accelerated homology search with MMseqs2," *Nature Methods*, Oct 2025, DOI [10.1038/s41592-025-02819-8](https://doi.org/10.1038/s41592-025-02819-8) | Backbone of ColabFold/Foldseek benchmarks |
| ESMFold | Hýsková et al., *Front. Genet.*, Jan 2026, DOI [10.3389/fgene.2025.1715037](https://doi.org/10.3389/fgene.2025.1715037) | AF2/ESMFold/OmegaFold benchmark |
| Boltz-1 | King, "On fine-tuning Boltz-2 for protein-protein affinity prediction," arXiv, Dec 2025, [arXiv:2512.06592](https://arxiv.org/abs/2512.06592) | Boltz/AF3/Chai benchmark suite |
| RoseTTAFold | Compared in AF3Complex / structure benchmarks 2025, DOI [10.1093/bioinformatics/btaf432](https://doi.org/10.1093/bioinformatics/btaf432) | Structure benchmarks |

## Genomics & single-cell

| Tool | Recent-usage anchor | Benchmark / Framework |
|---|---|---|
| Scanpy | Sun et al., "scDown: A Pipeline for Single-Cell RNA-Seq Downstream Analysis," *Int. J. Mol. Sci.*, May 2025, DOI [10.3390/ijms26115297](https://doi.org/10.3390/ijms26115297) | Biomni; "Benchmarking LLM-based agents for single-cell omics analysis" (*Genome Biology* 2026); Paper2Agent |
| scvi-tools | scverse × Biomni integration, 2025, per Biomni bioRxiv [10.1101/2025.05.30.656746](https://doi.org/10.1101/2025.05.30.656746) | Biomni framework; single-cell omics agent benchmark |
| GATK | WGS variant-calling pipeline assessment in monozygotic twins, *Briefings in Bioinformatics*, 2025, DOI [10.1093/bib/bbaf652](https://doi.org/10.1093/bib/bbaf652) | Biomni framework |
| samtools | Same WGS pipeline assessment, *Briefings in Bioinformatics*, 2025, DOI [10.1093/bib/bbaf652](https://doi.org/10.1093/bib/bbaf652) | Biomni framework |
| PLINK | Bundled tool in Biomni, *Science* 2026, DOI [10.1126/science.adz4351](https://doi.org/10.1126/science.adz4351) | Biomni framework |
| IQ-TREE | Bundled tool in Biomni, bioRxiv [10.1101/2025.05.30.656746](https://doi.org/10.1101/2025.05.30.656746) | Biomni framework |
| GCTA | Bundled tool in Biomni, bioRxiv [10.1101/2025.05.30.656746](https://doi.org/10.1101/2025.05.30.656746) | Biomni framework |
| MACS2 | Bundled tool in Biomni, bioRxiv [10.1101/2025.05.30.656746](https://doi.org/10.1101/2025.05.30.656746) | Biomni framework |
| LUMPY | Bundled tool in Biomni, bioRxiv [10.1101/2025.05.30.656746](https://doi.org/10.1101/2025.05.30.656746) | Biomni framework |

## Gene editing

| Tool | Recent-usage anchor | Benchmark / Framework |
|---|---|---|
| CHOPCHOP | Saraswat & Ranjan, "Unlocking the potential of CRISPR tools and databases," *Front. Plant Sci.*, Jul 2025, DOI [10.3389/fpls.2025.1563711](https://doi.org/10.3389/fpls.2025.1563711) | CRISPR-GPT framework |
| CRISPOR | Same *Front. Plant Sci.* review, 2025, DOI [10.3389/fpls.2025.1563711](https://doi.org/10.3389/fpls.2025.1563711) | CRISPR-GPT framework |
| Cas-OFFinder | Jasieniecka & Domingues, "CRISPR-Cas9 and Its Bioinformatics Tools: A Systematic Review," Apr 2025, DOI [10.3390/cimb47050307](https://doi.org/10.3390/cimb47050307) | CRISPR-GPT framework |
| CRISPRPick/CRISPick | Huang et al., "CRISPR-GPT for agentic automation of gene-editing experiments," *Nat. Biomed. Eng.*, 2025, DOI [10.1038/s41551-025-01463-z](https://doi.org/10.1038/s41551-025-01463-z) | CRISPR-GPT framework |

## Materials & MLIPs

Note: the materials machine-learned interatomic potentials share one dominant benchmark, **Matbench Discovery** (Riebesell et al., *Nature Machine Intelligence* 7:836–847, June 2025, DOI [10.1038/s42256-025-01055-1](https://doi.org/10.1038/s42256-025-01055-1)), which evaluated 13 models. Published F1 ranking for thermodynamic-stability prediction: EquiformerV2+DeNS > Orb > SevenNet > MACE > CHGNet > M3GNet > ALIGNN > MEGNet > CGCNN.

| Tool | Recent-usage anchor | Benchmark / Framework |
|---|---|---|
| MACE / MACE-MP-0 | Anam et al., "Comprehensive Assessment and Benchmark of Large Atomistic Foundation Models for Phonons," *Adv. Intelligent Discovery*, 2025, DOI [10.1002/aidi.202500075](https://doi.org/10.1002/aidi.202500075) | Matbench Discovery (ranked 4th of 13 by initial F1) |
| CHGNet | Same phonon benchmark, 2025, DOI [10.1002/aidi.202500075](https://doi.org/10.1002/aidi.202500075) | Matbench Discovery (ranked 5th of 13) |
| M3GNet | "Universal ML interatomic potentials are ready for phonons," *npj Comput. Mater.*, 2025, DOI [10.1038/s41524-025-01650-1](https://doi.org/10.1038/s41524-025-01650-1) | Matbench Discovery (ranked 6th of 13) |
| MatterSim | Same phonon *npj* paper, 2025, DOI [10.1038/s41524-025-01650-1](https://doi.org/10.1038/s41524-025-01650-1) | Matbench Discovery |
| Orb | Same phonon *npj* paper, 2025, DOI [10.1038/s41524-025-01650-1](https://doi.org/10.1038/s41524-025-01650-1) | Matbench Discovery (ranked 2nd of 13) |
| SevenNet | Same phonon *npj* paper, 2025, DOI [10.1038/s41524-025-01650-1](https://doi.org/10.1038/s41524-025-01650-1) | Matbench Discovery (ranked 3rd of 13) |
| matminer | Adapted as a task in ScienceAgentBench (Instance ID 3), [arXiv:2410.05080](https://arxiv.org/abs/2410.05080) | ScienceAgentBench |
| pymatgen | MatClaw autonomous materials agent (2026), uses the pymatgen QA suite, [arXiv:2604.02688](https://arxiv.org/abs/2604.02688) | MatTools benchmark; MatClaw framework |
| ASE | APEX automated cloud-native property explorer, *npj Comput. Mater.* 2025, DOI [10.1038/s41524-025-01580-y](https://doi.org/10.1038/s41524-025-01580-y) | MatTools ecosystem |
| Materials Project | Powers pymatgen/Matbench Discovery data, 2025, DOI [10.1038/s42256-025-01055-1](https://doi.org/10.1038/s42256-025-01055-1) | Matbench Discovery data source |
| OQMD | Used in the uMLP phonon evaluation (2429 OQMD crystals), *Adv. Intelligent Discovery* 2025, DOI [10.1002/aidi.202500075](https://doi.org/10.1002/aidi.202500075) | — |

## Chemistry & drug discovery

| Tool | Recent-usage anchor | Benchmark / Framework |
|---|---|---|
| AiZynthFinder | Saigiridharan et al., "AiZynthFinder 4.0," *J. Cheminform.*, 2024; enhanced-MCTS retrosynthesis, *J. Chem. Inf. Model.*, 2025, DOI [10.1021/acs.jcim.5c00417](https://doi.org/10.1021/acs.jcim.5c00417) | Syntheseus benchmark; PaRoutes |
| ASKCOS | Tu et al., "ASKCOS: Open-Source, Data-Driven Synthesis Planning," *Acc. Chem. Res.* 58(11):1764, 2025, DOI [10.1021/acs.accounts.5c00155](https://doi.org/10.1021/acs.accounts.5c00155) | Syntheseus; ChemCrow (uses RXN) |
| Syntheseus | Maziarz et al., "Re-evaluating Retrosynthesis Algorithms with Syntheseus," *Faraday Discuss.* 256:568, 2025 | It IS the benchmark |
| DeepChem | Adapted as a ScienceAgentBench task source, [arXiv:2410.05080](https://arxiv.org/abs/2410.05080) | ScienceAgentBench; ChemToolAgent |
| RDKit | ChemAmp / ChemToolAgent (2025) use RDKit as a core tool, [arXiv:2505.21569](https://arxiv.org/abs/2505.21569) | ChemCrow, ChemToolAgent, CACTUS frameworks |
| AutoDock Vina | Zayed, "Optimizing protein-ligand docking through ML: algorithm selection with AutoDock Vina," *Discov. Chem.*, 2025, DOI [10.1007/s44371-025-00246-4](https://doi.org/10.1007/s44371-025-00246-4) | DiffDock/PoseBusters docking benchmarks |
| DiffDock | "Deep Learning for Protein-Ligand Docking: Are We There Yet?" (PoseBench), 2024–2025, [arXiv:2405.14108](https://arxiv.org/abs/2405.14108) | PoseBench / PoseBusters |
| gnina | Same PoseBench comparison paper, 2024/25, [arXiv:2405.14108](https://arxiv.org/abs/2405.14108) | PoseBench |
| Psi4 | "Learning Molecular Conformational Energies Using Semilocal Density Fingerprints," *J. Phys. Chem. Lett.* 16:13083, Dec 2025, DOI [10.1021/acs.jpclett.5c02222](https://doi.org/10.1021/acs.jpclett.5c02222) | QCArchive/QCEngine ecosystem |
| PySCF | Pu & Sun, "Enhancing PySCF-based quantum chemistry simulations," *APL Comput. Phys.* 1(1):016101, Sep 2025, DOI [10.1063/5.0285025](https://doi.org/10.1063/5.0285025) | — |
| xtb | FRAGMENT multiscale framework (interfaces xTB), ChemRxiv 2025, DOI [10.26434/chemrxiv-2025-1k4k6-v2](https://doi.org/10.26434/chemrxiv-2025-1k4k6-v2) | — |
| Zeo++ | ChatMOF uses Zeo++ for accessible-surface-area calculation, DOI [10.1038/s41467-024-48998-4](https://doi.org/10.1038/s41467-024-48998-4) | ChatMOF framework |
| PORMAKE | ChatMOF uses PORMAKE genetic-algorithm generator, DOI [10.1038/s41467-024-48998-4](https://doi.org/10.1038/s41467-024-48998-4) | ChatMOF framework |
| LAMMPS | Gravelle et al., "A Set of Tutorials for the LAMMPS Simulation Package," *LiveCoMS* 6(1):3037, 2025, DOI [10.33011/livecoms.6.1.3037](https://doi.org/10.33011/livecoms.6.1.3037) | — |
| MOFTransformer | ChatMOF (Kang & Kim), *Nat. Commun.* 2024; SciToolAgent 2025 | ChatMOF, SciToolAgent frameworks |
| RASPA2 | ChatMOF / SciToolAgent MOF screening, DOI [10.1038/s41467-024-48998-4](https://doi.org/10.1038/s41467-024-48998-4) | ChatMOF, SciToolAgent |

## Databases bundled inside Biomni (framework association only)

UniProt, GWAS Catalog, Ensembl, ClinVar, dbSNP, EMDB, GEO, gnomAD, InterPro, KEGG, and Reactome are all explicitly bundled as databases inside **Biomni** (bioRxiv [10.1101/2025.05.30.656746](https://doi.org/10.1101/2025.05.30.656746); *Science* 2026, DOI [10.1126/science.adz4351](https://doi.org/10.1126/science.adz4351), which reports "59 comprehensive biomedical databases"). This confirms the framework association only — a standalone "most recent usage" paper per database was not individually traced and is not claimed here.
