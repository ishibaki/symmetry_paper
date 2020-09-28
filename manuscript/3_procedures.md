# Materials and Methods

## Fly lines

引用の記入方法に注意

*Canton-S* was used as wild-type.
The following mutants were used:
*emc^AP6^*, an amorphic allele[@Ellis1994] (Bloomington #36544);
*da^10^*, an amorphic allele[@Wulbeck1994] (Bloomington #5531);
and *MyoID^K2^*, an amorphic allele[@Petzoldt2012].
The following UAS lines were used:
*UAS-emc::GFP*[@Popova2011];
*UAS-da* (Bloomington #51669)[@Giebel1997];
*UAS-MyoIC*[@Hozumi2006];
*UAS-MyoID::mRFP*[@Hatori2014];
and *UAS-myr::GFP*[@Pfeiffer2012].
The following *Gal4*-driver lines were used:
*NP2432* (Kyoto DGRC #104201)[@Hayashi2002] for the analysis of fixed cell chirality index,
and *byn-Gal4*[@Hozumi2006] for the analysis of live cell chirality index.
Mutations on the second chromosome and third chromosome were balanced with *CyO, P{en1}wg^en11^* and *TM3, P{GAL4-twi.G}2.3, P{UAS-2xEGFP}AH2.3, Sb^1^ Ser^1^*, respectively.
All genetic crosses were carried out at $25^{\circ} \mathrm{C}$ on a standard *Drosophila* culture medium.

## Live Imaging and laterality score

To visualize the cell membrane of the hindgut epithelium, the expression of *UAS-myr::GFP* was driven by *byn-Gal4* using GAL4/UAS system[@Brand1993].
*Drosophila* embryos were dechorionated and placed on grape juice agar plates.
Embryos of the appropriate genotypes were selected at early stage 12 under a fluorescence microscopy and mounted dorsal side up on double sticky tape on slide glasses.
These embryos were overlaid by oxygen-permeable Halocarbon oil 27 (Sigma, USA) and a coverslip with spacers of 0.17-0.25 mm-thick coverslips.
The live images of apical cell-boundaries in hindgut epithelium were obtained with a scanning laser confocal microscope, LSM 880 (Carl Zeiss, Germany) before the onset of the hindgut rotation.
After the imaging, the embryos were continuously cultured at $25^{\circ} \mathrm{C}$ for 3 hours and the rotational directions of the hindgut were evaluated.
As laterality score, the hindgut rotating to the counter-clockwise and clockwise directions was scored 1 and 0, respectively.
When the hindgut did not rotate, the laterality score was marked as 0.5.

## Analysis of cell chirality index

Cell chirality was analyzed as previously described[@Ishibashi2019].
Briefly, we obtained the images of apical cell boundaries, which were detected by Myr::GFP signal, in the dorsal part of the embryonic hindgut just before its rotation (at stage 12) using a confocal microscope (LSM880, Carl Zeiss, Germany).
Based on these images, the angles ($\theta$) between the anterior-posterior axis of the hindgut tube and each cell boundary were determined by ImageJ Fiji v.2.0.0[@Schindelin2012].
To quantify the LR asymmetric slanting of the apical cell boundaries in the hindgut epithelial cells, a cell chirality index was calculated as $\frac{N_{R} - N_{L}}{N_{R} + N_{L}}$,
where N~R~ was the number of boundaries with $0^{\circ} < \theta <  90^{\circ}$ and $-180^{\circ} < -90^{\circ}$, and N~L~ was the number of boundaries with $-90^{\circ} < \theta <  0^{\circ}$ and $90^{\circ} < \theta < 180^{\circ}$, for each embryo.
The chirality index was measured in a double-blind manner, in which the person analyzing the cell boundaries did not know the genotypes of the embryos and the prospective rotational direction of the hindgut.

## Statistical analysis

To test the correlation between the mean cell chirality and the mean of the laterality score in fixed embryos or between the live chirality index and the laterality score in each living embryo, logistic models were used[@Campbell1991].
As a null hypothesis, naive models were used[@Campbell1991].
For the fixed embryos, the mean of laterality score was treated as a response variable, and the mean of the chirality index was treated as an explanatory variable.
All statistical analyses were performed using R software v.3.6.3[@Rcoreteam2020].
Graphs were prepared using Matplotlib v.3.0.3 in Python v.3.6.4[@Rossum1995; @Hunter2007].

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
9_acknowledgements.md
-->
