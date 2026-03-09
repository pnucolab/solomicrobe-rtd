Version History
===============

This page documents the release history of SoloMicrobe, including new features, improvements, and bug fixes.

SoloMicrobe 1.0 (March 2026)
-----------------------------

Initial public release of SoloMicrobe.

**Features**

- Probe design pipeline for microbial gene and transcript sequences
- Alignment-based specificity filtering against host transcriptomes (human, mouse)
- Screening against co-residing microbiome genomes (gut, oral, skin, vaginal)
- Configurable probe length (20–50 bp), k-mer length (min 14 bp), and mismatch tolerance (0–2)
- Interactive genome browser (JBrowse) for visualizing probe positions on gene sequences
- Detailed alignment tables with mismatch counts and filtering for probe sequence input
- Safe probe scoring with downloadable results
- Real-time job progress monitoring
- Web interface with FASTA sequence input

**Reference Databases**

- Human transcriptome (GENCODE)
- Mouse transcriptome (GENCODE)
- Human gut microbiome (MGnify v2.0.2)
- Human oral microbiome (MGnify v1.0.1)
- Human skin microbiome (MGnify v1.0)
- Human vaginal microbiome (MGnify v1.0)
- Mouse gut microbiome (MGnify v1.0)

**Technical Stack**

- Backend: FastAPI + Celery
- Frontend: Svelte
- Alignment: RazerS3
- Visualization: JBrowse 2
- Documentation: Read the Docs
