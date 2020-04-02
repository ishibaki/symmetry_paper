# Material and methods

## Fly lines

*Canton-S* was used as wild-type (WT).
To analyze the relationship between live cell chirality and the hindgut rotational direction, *emc^AP6^*, an amorphic allele of *emc*, was used [@Ellis1994, Bloomington #36544].
To visualize the cell membrane, *UAS-myr::GFP* was driven by *byn-Gal4*, a hindgut epithelium-specific driver [@Hozumi2006].
Mutations on the second chromosome and third chromosome were balanced with *CyO, P{en1}wg^en11^* and *TM3, P{GAL4-twi.G}2.3, P{UAS-2xEGFP}AH2.3, Sb^1^ Ser^1^*, respectively.
All genetic crosses were carried out at $25^{\circ} \mathrm{C}$ on a standard *Drosophila* culture medium.

## Live Imaging and laterality score

Dechorionized *Drosophila* embryos were placed on grape juice agar plates.
Early stage 12 embryos of the appropriate genotype were selected under florescence microscopy and mounted dorsal side up on double sticky tape on slide glasses.
We added oxygen-permeable Halocarbon oil 27 (Sigma), and overlaid a coverslip of regular thickness over the embryos using 0.17-0.25 mm-thick coverslips as spacers.
We imaged embryos with a scanning laser confocal microscope, LSM 880 (Carl Zeiss, Germany).
After the live imaging, the embyors were cultured at $25^{\circ} \mathrm{C}$ for 3 hours, and evaluated the rotational direction of the hindgut.
When the hindgut rotated in counter-clockwise direction or in clockwise direction, we scored 1 or 0, respectively as laterality score.
When the hindgut did not rotate, we evaluated the laterality scorea as 0.5.

## Analysis of cell chirality index

Cell chirality was analyzed as previously described [@Ishibashi2019].
Briefly, we obtained the images of apical cell boundaries, which were detected by Myr::GFP signal, in the dorsal part of the embryonic hindgut just before its rotation (at stage 12) using a confocal microscope (LSM880, Carl Zeiss, Germany).
Based on these images, the angles ($\theta$) between the anterior-posterior axis of the hindgut tube and each cell boundary were determined by ImageJ Fiji v.2.0.0 [@Schindelin2012].
To quantify the LR asymmetric slanting of the apical cell boundaries in the hindgut epithelial cells, a chirality index was calculated as $\frac{N_{R} - N_{L}}{N_{R} + N_{L}}$,
where N~R~ was the number of boundaries with $0^{\circ} < \theta <  90^{\circ}$, and N~L~ was the number of boundaries with $-90^{\circ} < \theta <  0^{\circ}$, for each embryo.
The chirality index was measured in a double-blind manner, in which the person analyzing the cell boundaries did not know the rotational direction of the embryonic hindgut.

## Statistical analysis

To test the contribution of the cell chirality to explain the laterality score, generalized linear models (GLMs) were used.
As a null hypothesis, naive models were used.
Laterality score was treated as a response variable, and mean of the chirality index was treated as an explanatory variable.
All statistical analyses were performed using R software v.3.6.3 [@Rcoreteam2020].
Graphs were prepared using Matplotlib v.3.0.3 in Python v.3.6.4 [@Rossum1995; @Hunter2007].

\clearpage

\mbox{}

\newpage

<!--
0_metadata/meta0.md
0_metadata/meta1.md
1_abstract.md
2_introduction.md
3_procedures.md
4_results.md
5_discussion.md
6_figs.md
7_references.md
8_supplements.md
-->
