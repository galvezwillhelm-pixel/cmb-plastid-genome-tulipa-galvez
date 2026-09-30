# Characterization of a Plastid Genome: *Tulipa greigii*

## Student Information

- **Student:** Willhelm Wien Galvez
- **Course:** Cell and Molecular Biology
- **Section:** B
- **Date Retrieved:** 30 September 2026

---

# Selected Plant and Genome

- **Genus:** *Tulipa*
- **Species:** *Tulipa greigii*
- **Family:** Liliaceae
- **Organelle:** Chloroplast (plastid)
- **Accession:** NC_087048.1
- **Genome:** Complete chloroplast genome
- **Genome size:** 152,006 bp
- **Topology:** Circular
- **Source:** NCBI Reference Sequence (RefSeq)

**NCBI record:** https://www.ncbi.nlm.nih.gov/nuccore/NC_087048.1?report=genbank

The selected sequence is the complete chloroplast genome of *Tulipa greigii*. The NCBI record identifies NC_087048.1 as a complete chloroplast genome and describes the molecule as circular DNA.

The NC_087048.1 record states that the reference sequence is identical to PP335814, which was characterized in a published study of *Tulipa* chloroplast genomes.

---

# Evidence That the Genome Is Complete

The selected sequence represents a complete plastid genome rather than a DNA barcode, partial fragment, raw-read dataset, or nuclear sequence.

Evidence includes:

1. The NCBI definition identifies the sequence as **“chloroplast, complete genome.”**
2. The genome is **152,006 bp** long.
3. The molecule is described as **circular DNA**.
4. The record contains extensive annotation across the genome.
5. The annotation includes protein-coding genes, tRNA genes, and rRNA genes.
6. The genome has the typical four-part plastid organization consisting of LSC, IRa, SSC, and IRb regions.
7. The sequence is available as an annotated GenBank/RefSeq record rather than as a short barcode or raw sequencing dataset.

These features support that NC_087048.1 represents a complete annotated chloroplast genome.

---

# Data Retrieval

- **Database:** NCBI Nucleotide / RefSeq
- **Accession:** NC_087048.1
- **Species:** *Tulipa greigii*
- **Sequence type:** Complete chloroplast genome
- **Retrieval date:** 30 September 2026
- **FASTA file:** `Tulipa_greigii_NC_087048.1.fasta`
- **GenBank file:** `Tulipa_greigii_NC_087048.1.gb`

The FASTA sequence and annotated GenBank record were downloaded from NCBI and uploaded to Galaxy for sequence characterization.

---

# Galaxy Analysis

## Galaxy History

The analysis was performed using Galaxy with the history:

`Plastid_Tulipa_Galvez`

The complete chloroplast FASTA sequence was uploaded to Galaxy and renamed:

`Tulipa greigii — NC_087048.1 — Complete Chloroplast Genome`

The annotated GenBank record was also uploaded and renamed:

`Tulipa greigii — NC_087048.1 — Annotated GenBank`

## Fasta Statistics

The Galaxy **Fasta Statistics** tool was used to characterize the uploaded FASTA sequence.

| Characteristic | Galaxy Result |
|---|---:|
| Number of sequences | 1 |
| Genome size | 152,006 bp |
| A | 48,665 |
| T | 47,670 |
| C | 27,586 |
| G | 28,081 |
| N | 4 |
| GC content | 36.62% |
| Number of gaps | 4 |
| Bases excluding N | 152,002 bp |

The Galaxy analysis confirmed that the uploaded FASTA contains **one sequence** with a length of **152,006 bp** and an overall GC content of **36.62%**.

---

# Galaxy Evidence

The Galaxy history `Plastid_Tulipa_Galvez` contains the uploaded FASTA sequence, the Fasta Statistics output, and the annotated GenBank record.

The Fasta Statistics output provides evidence for:

- One sequence
- 152,006-bp genome length
- 36.62% overall GC content
- Four ambiguous N bases
- Four gaps

The Galaxy evidence screenshot is stored in:

`figures/galaxy_fasta_statistics.jpeg`

---

# Genome Annotation Evidence

The NCBI Graphics view was used to visually examine the annotated chloroplast genome.

The graphical map displays numerous annotated genome features, including photosynthesis-related genes, ribosomal protein genes, RNA genes, and other chloroplast genes distributed across the genome.

The annotated GenBank record was also uploaded to Galaxy to preserve the genome annotation used during the characterization.

---

# Questions and Answers

## 1. What is the full scientific name, family, accession/version, source, and genome size?

### Answer

The selected plant is *Tulipa greigii*, which belongs to the family **Liliaceae**.

The selected plastid genome is the complete chloroplast genome with NCBI RefSeq accession **NC_087048.1**.

- **Scientific name:** *Tulipa greigii*
- **Family:** Liliaceae
- **Accession/version:** NC_087048.1
- **Source:** NCBI Nucleotide/RefSeq
- **Genome:** Complete chloroplast genome
- **Genome size:** 152,006 bp
- **Topology:** Circular

The NCBI record identifies NC_087048.1 as *Tulipa greigii* chloroplast, complete genome.

---

## 2. What evidence shows that this is a complete plastid genome rather than a barcode, fragment, or nuclear sequence?

### Answer

Several pieces of evidence show that NC_087048.1 is a complete plastid genome:

1. The NCBI definition explicitly identifies it as a **chloroplast, complete genome**.
2. The sequence is **152,006 bp** long.
3. The molecule is described as **circular DNA**.
4. The record contains extensive genome annotation.
5. The annotation includes protein-coding genes, tRNA genes, and rRNA genes.
6. The genome has the typical four-part plastid organization consisting of an LSC region, two IR regions, and an SSC region.
7. The sequence is available as an annotated GenBank/RefSeq record rather than as a short barcode or raw sequencing dataset.

Therefore, the sequence represents a complete annotated chloroplast genome rather than a barcode, fragment, raw-read dataset, or nuclear sequence.

---

## 3. How is the genome organized? Give the LSC, SSC, and IR sizes.

### Answer

The *T. greigii* chloroplast genome has the typical quadripartite organization of a plant plastome.

| Region | Size |
|---|---:|
| Large Single Copy (LSC) | 82,169 bp |
| Inverted Repeat A (IRa) | 26,330 bp |
| Small Single Copy (SSC) | 17,172 bp |
| Inverted Repeat B (IRb) | 26,330 bp |
| **Total** | **152,006 bp** |

The organization can be represented as:

**LSC → IRa → SSC → IRb**

The two IR regions are duplicated portions of the plastid genome and separate the LSC and SSC regions.

---

## 4. What is the gene content? How many total genes, protein-coding genes, tRNAs, rRNAs, pseudogenes, and duplicated genes are present?

### Answer

The *T. greigii* chloroplast genome contains **131 functional genes**.

| Gene category | Number |
|---|---:|
| Total functional genes | 131 |
| Protein-coding genes | 85 |
| tRNA genes | 38 |
| rRNA genes | 8 |
| Duplicated genes in IR regions | 18 |

The reported pseudogenes are:

- *ycf15*
- *ycf68*

The 18 duplicated genes in the IR regions include:

### Duplicated protein-coding genes

- *ndhB*
- *rpl2*
- *rpl23*
- *rps7*
- *rps12B*
- *ycf2*

### Duplicated RNA genes

- *rrn4.5*
- *rrn5*
- *rrn16*
- *rrn23*

### Duplicated tRNA genes

- *trnA-UGC*
- *trnH-GUG*
- *trnI-CAU*
- *trnI-GAU*
- *trnL-CAA*
- *trnN-GUU*
- *trnR-ACG*
- *trnV-GAC*

Genes located inside an inverted repeat can occur in two copies because IRa and IRb are duplicated regions of the chloroplast genome.

---

## 5. Give at least eight protein-coding genes from different functional groups and their functions.

### Answer

| Gene | Functional group | Function |
|---|---|---|
| *rbcL* | Carbon fixation | Encodes the large subunit of Rubisco, involved in carbon fixation |
| *psaA* | Photosystem I | Encodes a core Photosystem I reaction-center protein |
| *psbA* | Photosystem II | Encodes the D1 reaction-center protein of Photosystem II |
| *atpA* | ATP synthase | Encodes a component of the ATP synthase complex |
| *petA* | Electron transport | Encodes a component of the cytochrome b6/f complex |
| *rpoB* | Transcription | Encodes a subunit of the plastid-encoded RNA polymerase |
| *rpl2* | Translation | Encodes a large ribosomal-subunit protein |
| *ndhF* | NADH dehydrogenase | Encodes a component of the plastid NADH dehydrogenase complex |
| *matK* | RNA processing | Encodes a maturase involved in RNA splicing |
| *accD* | Metabolism | Encodes a component of acetyl-CoA carboxylase |

These genes represent different plastid functions, including photosynthesis, electron transport, ATP production, transcription, translation, RNA processing, and metabolism.

---

## 6. What RNA genes are present? Give examples of tRNAs and at least two intron-containing genes.

### Answer

The genome contains:

- **38 tRNA genes**
- **8 rRNA genes**

The rRNA genes include:

- *rrn4.5*
- *rrn5*
- *rrn16*
- *rrn23*

Examples of tRNA genes include:

- *trnA-UGC*
- *trnH-GUG*
- *trnI-CAU*
- *trnI-GAU*
- *trnL-CAA*
- *trnN-GUU*
- *trnR-ACG*
- *trnV-GAC*

The published characterization reported **28 intron-containing genes**, with intron lengths ranging from approximately **540 bp to 2,620 bp**.

Examples include:

- *ndhA*
- *ndhB*
- *rpl2*
- *rpl16*
- *rps16*
- *rpoC1*
- *petB*
- *petD*
- *atpF*

The genes *clpP* and *ycf3* contain two introns.

The *matK* gene is located within the intron of the *trnK* gene.

---

## 7. Are there pseudogenes, gene losses, duplications, rearrangements, or unusual features?

### Answer

The reported pseudogenes are:

- *ycf15*
- *ycf68*

The genome contains **18 duplicated genes in the IR regions**. These include protein-coding genes, rRNA genes, and tRNA genes.

The published study did not report a specific gene loss unique to *T. greigii*. The notable non-functional gene-like features reported for this plastome were the pseudogenes *ycf15* and *ycf68*.

The overall plastid genome structure and gene arrangement are highly conserved among the four *Tulipa* plastomes examined in the published study.

No major genome-wide rearrangement was reported for the *T. greigii* plastome in that study.

A notable feature is the presence of *matK* within the intron of *trnK*. Another important structural feature is the duplication of genes located in the IR regions.

---

## 8. What is the GC content? Give two other notable sequence or structural observations based on Galaxy and the annotation.

### Answer

The Galaxy Fasta Statistics analysis gave an overall GC content of **36.62%**.

Galaxy results:

- **Number of sequences:** 1
- **Genome length:** 152,006 bp
- **GC content:** 36.62%
- **A:** 48,665
- **T:** 47,670
- **C:** 27,586
- **G:** 28,081
- **N:** 4
- **Number of gaps:** 4

### Observation 1: Regional GC differences

The published study reported:

- **Whole genome:** 36.62%
- **LSC:** 34.53%
- **SSC:** 30.01%
- **IR:** 42.01%

Thus, the IR regions have a higher GC content than the LSC and SSC regions.

### Observation 2: Conserved quadripartite structure

The genome has the characteristic:

**LSC → IR → SSC → IR**

organization of a typical land-plant chloroplast genome.

The Galaxy analysis independently confirmed the complete sequence length and overall GC content.

---

## 9. Give five similarities and five differences between plastid and mitochondrial genomes.

### Answer

### Similarities

1. Both are organelles containing their own DNA.
2. Both are separate from the nuclear genome.
3. Both contain genes and RNAs needed for organelle functions.
4. Both can occur in multiple copies within a cell.
5. Both have evolutionary histories associated with endosymbiotic origins.

### Differences

| Feature | Plastid Genome | Mitochondrial Genome |
|---|---|---|
| Cellular location | Chloroplast/plastid | Mitochondrion |
| Main function | Photosynthesis and plastid metabolism | Cellular respiration and energy production |
| Organization | Usually circular with LSC, SSC, and two IR regions in land plants | Plant mitochondrial genomes can have complex and multipart structures |
| Gene content | Includes photosynthesis, transcription, translation, and plastid metabolic genes | Mainly includes respiration-related genes and mitochondrial gene-expression genes |
| Relative size | Generally compact | Highly variable in plants |
| Copy number | Multiple copies can occur within plastids | Multiple copies can occur within mitochondria |
| Inheritance | Often maternal in angiosperms, with exceptions | Usually maternal in angiosperms, with exceptions |
| Recombination/structural change | Generally more structurally conserved | Plant mitochondrial genomes can undergo extensive recombination and rearrangement |
| Mutation/substitution pattern | Generally relatively conserved in many coding regions, with variation concentrated in particular regions | Plant mitochondrial genomes can show slow nucleotide substitution in coding genes while undergoing substantial structural change and recombination |
| Research applications | Plant identification, phylogeny, barcoding, comparative genomics | Mitochondrial evolution, cytoplasmic inheritance, and respiration-related studies |

---

## 10. What is the practical value of plastid genomes? What are their advantages and limitations compared with nuclear genomes?

### Answer

Complete plastid genomes are useful for:

- Plant species identification
- DNA barcoding
- Phylogenetic analysis
- Comparative genomics
- Population studies
- Evolutionary research
- Conservation genetics
- Molecular marker development
- Chloroplast evolution
- Biodiversity studies

### Advantages Compared With Nuclear Genomes

Plastid genomes are generally smaller and more compact than nuclear genomes. They contain conserved genes and variable regions that can be compared among plant species.

A complete plastid genome can provide many molecular markers from one organelle genome. Plastid inheritance is also often uniparental in flowering plants, which can be useful for studying cytoplasmic lineages.

Because plastid genomes are relatively compact and contain many conserved genes, they can be practical for comparative analysis and phylogenetic studies among plant species.

### Limitations

A plastid genome represents only the evolutionary history of the plastid lineage and does not represent the entire genetic history of the organism.

Plastid inheritance is often uniparental, so plastid phylogenies can differ from nuclear phylogenies. Hybridization and introgression can also produce differences between plastid and nuclear evolutionary histories.

The plastid genome also contains far fewer genes than the nuclear genome, so it cannot answer questions that depend on large numbers of nuclear genes or nuclear regulatory regions.

Nuclear genomes are also necessary for studying traits controlled by nuclear loci, including sex-linked traits in organisms that possess sex chromosomes.

### Research Question Better Suited to a Plastid Genome

**How does the complete chloroplast genome of *Tulipa greigii* compare with those of closely related *Tulipa* species, and which plastid regions are useful for distinguishing the species?**

### Research Question Better Suited to a Nuclear Genome

**Which nuclear genetic variants are associated with differences in flower characteristics or other complex traits among *Tulipa* populations?**

---

# Plastid Genome vs. Mitochondrial Genome Summary

| Feature | Plastid Genome | Mitochondrial Genome |
|---|---|---|
| Cellular location | Chloroplast/plastid | Mitochondrion |
| Main role | Photosynthesis, plastid metabolism, and plastid gene expression | Cellular respiration, energy production, and mitochondrial gene expression |
| Organization | Typically circular and quadripartite in land plants | Often structurally complex in plants |
| Relative size | Usually compact | Highly variable in plants |
| Gene content | Photosynthesis, transcription, translation, RNA, and metabolic genes | Mainly respiration-related and organelle gene-expression genes |
| Copy number | Multiple copies may occur | Multiple copies may occur |
| Inheritance | Often maternal in angiosperms, with exceptions | Usually maternal in angiosperms, with exceptions |
| Recombination | Generally more structurally conserved | Can undergo extensive recombination |
| Structural variation | Usually relatively conserved | Often highly variable in plants |
| Mutation/substitution pattern | Generally relatively conserved in many coding regions | Coding genes can have slow nucleotide substitution while the genome undergoes substantial structural change |
| Research applications | Plant identification, phylogeny, barcoding, comparative genomics | Mitochondrial evolution, cytoplasmic inheritance, and respiration-related research |

---

# Important Plastid Gene Groups

The genome contains several major gene groups.

## Photosynthesis

Examples:

- *psaA*
- *psaB*
- *psaC*
- *psaI*
- *psaJ*
- *psbA*
- *psbB*
- *psbC*
- *psbD*
- *psbE*
- *psbF*
- *psbH*
- *psbI*
- *psbJ*
- *psbK*
- *psbL*
- *psbM*
- *psbT*
- *psbZ*
- *rbcL*

## ATP Synthase

Examples:

- *atpA*
- *atpB*
- *atpE*
- *atpF*
- *atpH*
- *atpI*

## Cytochrome b6/f Complex

Examples:

- *petA*
- *petB*
- *petD*
- *petG*
- *petL*
- *petN*

## RNA Polymerase

Examples:

- *rpoA*
- *rpoB*
- *rpoC1*
- *rpoC2*

## Ribosomal Proteins

Examples:

- *rpl2*
- *rpl16*
- *rpl23*
- *rps7*
- *rps12*
- *rps15*

## NADH Dehydrogenase

Examples:

- *ndhA*
- *ndhB*
- *ndhC*
- *ndhD*
- *ndhE*
- *ndhF*
- *ndhG*
- *ndhH*
- *ndhI*
- *ndhJ*
- *ndhK*

## Other Notable Genes

- *matK* — RNA splicing
- *clpP* — plastid protease complex
- *accD* — acetyl-CoA carboxylase
- *cemA* — plastid envelope-associated function
- *ycf1*
- *ycf2*

---

# Key Terms

- **Plastome:** The genome of a plastid, including the chloroplast genome.
- **LSC:** Large Single Copy region of the chloroplast genome.
- **SSC:** Small Single Copy region of the chloroplast genome.
- **IR:** Inverted Repeat; a duplicated region found twice in the plastid genome.
- **CDS:** Coding DNA Sequence that contains information used to produce a protein.
- **tRNA:** Transfer RNA that carries amino acids during protein synthesis.
- **rRNA:** Ribosomal RNA that forms part of the ribosome.
- **Intron:** A sequence within a gene transcript that is removed during RNA processing.
- **Pseudogene:** A gene-like sequence that has lost its normal functional capacity.
- **GC content:** The percentage of guanine and cytosine bases in a DNA sequence.
- **Accession:** A unique identifier assigned to a biological sequence record.
- **Annotation:** Information identifying genes and other biological features within a sequence.
- **Topology:** The structural form of a DNA molecule, such as circular or linear.

---

# Plastid Genome Characterization Summary

| Characteristic | *Tulipa greigii* |
|---|---:|
| Genus | *Tulipa* |
| Species | *Tulipa greigii* |
| Family | Liliaceae |
| Accession | NC_087048.1 |
| Related identical sequence | PP335814 |
| Genome type | Chloroplast |
| Genome size | 152,006 bp |
| Topology | Circular |
| LSC | 82,169 bp |
| SSC | 17,172 bp |
| IRa | 26,330 bp |
| IRb | 26,330 bp |
| Total functional genes | 131 |
| Protein-coding genes | 85 |
| tRNA genes | 38 |
| rRNA genes | 8 |
| Duplicated genes in IRs | 18 |
| Reported pseudogenes | *ycf15*, *ycf68* |
| Intron-containing genes | 28 |
| Overall GC content | 36.62% |
| Galaxy sequence count | 1 |
| Galaxy gaps | 4 |

---

# Conclusion

The complete chloroplast genome of *Tulipa greigii* provides a useful example of a plant plastome that can be characterized using NCBI and Galaxy.

The genome is a circular 152,006-bp molecule with an LSC–IR–SSC–IR organization. It contains 131 functional genes, including 85 protein-coding genes, 38 tRNA genes, and 8 rRNA genes.

The Galaxy analysis confirmed one sequence with a genome length of 152,006 bp and an overall GC content of 36.62%. The annotated genome also demonstrates duplicated genes in the IR regions and reported pseudogenes such as *ycf15* and *ycf68*.

Overall, complete plastid genomes provide useful data for plant identification, phylogenetic analysis, comparative genomics, evolutionary research, conservation studies, and molecular marker development.

---

# References

1. **NCBI Reference Sequence.** *Tulipa greigii* chloroplast, complete genome. RefSeq accession NC_087048.1.

2. **Tussipkan, D., et al. (2024).** Kazakhstan tulips: comparative analysis of complete chloroplast genomes of four local and endangered species of the genus *Tulipa* L. *Frontiers in Plant Science*, 15, 1433253. DOI: https://doi.org/10.3389/fpls.2024.1433253

3. **Galaxy Project.** Galaxy platform for accessible and reproducible biomedical data analysis.

---

# Repository Contents

```text
cmb-plastid-genome-tulipa-galvez/
├── README.md
├── data/
│   ├── Tulipa_greigii_NC_087048.1.fasta
│   └── Tulipa_greigii_NC_087048.1.gb
├── results/
│   └── characterization_table.md
└── figures/
    └── galaxy_fasta_statistics.jpeg
