# Results

## A logistic model significantly explained the correlation between the enantiomorphic stats of cell chirality and the LR directionality of hindgut rotation

The *Drosophila* hindgut is first formed as a bilaterally symmetric invagination whose anterior part curves ventrally at early stage 12 ([@fig:fig1]A most left panel)[@Hozumi2006].
Then, it gradually rotates counterclockwise 90 degrees as a view from the posterior ([@fig:fig1]A, middle two panels).
Consequently, this rotation makes the hindgut curved towards the right at the end of stage 13 ([@fig:fig1]A, most right panel).
The hindgut epithelium has a typical apical-basal polarity, and the inner surface of the hindgut corresponds to the apical surface.
Before the rotation of the hindgut, cell chirality of the hindgut epithelial cells is detected in the shape of their apical surface, as the frequency of cell boundaries that slant left or right with respect to the anterior-posterior axis of the hindgut tube shows deviations according to the genetic conditions[@Ishibashi2019].
For example, cell-boundaries slanting to the left appeared more often than that of the right in wild type ([@fig:fig1]B, left).
However, such LR bias found in the angle of cell boundaries are dissolved after the completion of the hindgut rotation ([@fig:fig1]B, right).
To quantitatively analyze the cell chirality, "chirality index" was formulated previously[@Ishibashi2019].
The apical cell boundaries were visualized, and the origin of two-dimensional coordinate corresponding the anterior-posterior and left-right axes are placed on a vertex ([@fig:fig1]C most left).
The cell boundaries exist in the first and third quadrants (shown in orange) and the second and fourth quadrants (shown in blue) are defied as Right (orange lines) and Left (blue liens), respectively ([@fig:fig1]C left and middle).
Then, the total numbers of Right and Left were represented by N-Right ($N_{R}$) and N-Left ($N_{L}$), respectively ([@fig:fig1]C, right).
The average values of cell chirality index obtained from embryos (numbers are indicated in [@fig:fig2]B as $N_{x}$) with each genotype was referred to as "mean cell chirality index."

We previously showed that the mean cell chirality index strongly correlated with the ratio of the normal hindgut laterality in embryos with various genotype[@Ishibashi2019].
To investigate a causal association between the enantiomorphic stats of cell chirality and the LR directions of the hindgut rotation, we here analyzed the mathematical characteristics of the correlation between the mean cell chirality index and the rotational direction of the hindgut.
We scored the rotational direction of the hindgut in each embryo as a "laterality score", in which the hindgut of normal LR asymmetry, non-laterality (bilateral symmetry), and inverse LR asymmetry was scored 1, 0.5, and 0, respectively ([@fig:fig2]A).
The mean of the laterality score was calculated in embryos with each genotype ([@fig:fig2]B, left).
Besides the eight genetic conditions analyzed in the previous study, we examined two additions to study the correlation between the mean cell chirality index and the mean of the laterality score ([@fig:fig2]B)[@Ishibashi2019].
As the newly added conditions, double mutant embryos of *da^10^* and *emc^AP6^* (*da^10^; emc^AP6^*) were analyzed ([@fig:fig2]B).
Our previous analysis revealed that *da* mutation suppresses the LR defects of the hindgut in *emc* mutant, because *emc* mutant induces the LR defects through the hyper-activation of *da*[@Ishibashi2019].
Additionally, embryos overexpressing *UAS-MyoIC*, which has the sinistral activity of the LR asymmetric development, in the hindgut epithelium were examined ([@fig:fig2]B)[@Hozumi2008; @Okumura2015; @Lebreton2018].

We fitted the logistic model (dotted line) with the chirality index as an explanatory valuable and the mean of the laterality score as an objective variable ([@fig:fig2]B).
The chirality index significantly explained the mean of laterality score
(Quasibinomial generalized linear model (GLM), two-tailed t-test) ([@fig:fig2] B, [@tbl:tbl1]).
<!-- Intercept: t(8) = -4.042, p = 0.003723
Chirality Index: t(8) = -5.992, p = 0.000326 -->

## Cell chirality index predicts the LR directions of future hindgut rotation in live embryos

Considering that cell chirality appears before the initiation of the hindgut rotation, the significant correlation between the mean cell chirality index and the mean of laterality score suggested that cell chirality index of each embryo may determine the LR directionality of the hindgut rotation in an individual.
In this case, the chirality index in each live embryo should predict the left or right directionality of the future hindgut rotation afterwards.
To test this possibility, we developed a new procedure to obtain the cell chirality index in the hindgut of live embryos and then determine the subsequent LR directionality of the hindgut rotation.
In this system, the apical cell boundaries of the hindgut epithelium were visualized in live embryos at early stage 12 under a confocal laser microscope, and these embryos were continuingly cultured another three hours ([@fig:fig3]A).
At that point, the rotation of the hindgut was completed under these conditions in wild-type ([@fig:fig3]A right).
The cell chirality index obtained from this procedure was designated as "live cell chirality index," and the laterality score of each embryo was marked 1, 0.5, and 0, as the hindgut subsequently showed normal LR asymmetry, non-laterality (bilateral symmetry), and inverse LR asymmetry, respectively.

To investigate whether the live cell chirality index correlates with the rotational direction of the hindgut, we found that the LR-randomization phenotypes of *emc^AP6^* homozygote was appropriate for this purpose.
Only in *emc^AP6^* mutant among the ten different mutants examined here, the mean cell chirality index was nearly zero with deviation ranging from plus to minus values ([@fig:fig2]B).
In addition, the hindgut of these embryos shows normal and inverse LR asymmetry as well as non-laterality[@Ishibashi2019].
Thus, we speculated that each individual embryo has stochastically fluctuated cell chirality, which may induce the hindgut rotation to the direction corresponding the cell chirality index of each.
Based on this assumption, we evaluated the consistency between the chirality indexes obtained from fixed and live embryos, we analyzed the mean of live chirality indexes in wild-type and *emc^AP6^* homozygous embryos.
The mean live chirality indexes of wild-type and *emc^AP6^* homozygous embryos were $-0.12 \pm 0.04$ and $-0.02 \pm 0.03$, respectively, which were very similar to those of fixed embryos as reported before (wild-type, $-0.11 \pm 0.03$; *emc^AP6^* homozygote, $0.01 \pm 0.02$), although these mean values of live cell chirality indexes were not significantly different in this experiment (Two-tailed t-test, $p = 0.069217$)[@Ishibashi2019].
We also found that each individual embryo of *emc^AP6^* homozygote showed a broad range of live chirality indexes, which distributed from plus to minus values, as compared with that of wild-type ([@fig:fig3]B).
<!--
Live cell chirality:
    CS       -0.117237 +- 0.035853
    emcAP6   -0.022627 +- 0.031554
Fixed cell chirality:
    CS       -0.108681 +- 0.025608
    emcAP6    0.011422 +- 0.015463
-->

Given that the values of live chirality index agreed well with those of cell chirality index in the fixed embryos, we next conducted a statistical correlation analysis between the live cell chirality index and laterality score of each individual *emc^AP6^* mutant embryo.
We fitted the logistic model (solid line) with the live chirality index as an explanatory variable and the laterality score of each embryo as an objective variable and found that live cell chirality, which was determined prior to the onset of the hindgut rotational direction
(Quasibinomial GLM, two-tailed t-test, $p < 0.01$; [@fig:fig3]C; [@tbl:tbl2]).
Importantly, the logistic regression model (dotted line) obtained the fixed embryos with various genetic conditions as described in [@fig:fig2] significantly fitted the data obtained from each livin *emc^AP6^* mutant embryo
(Quasibinomial GLM, likelihood ratio test, $\chi^{2}_{1} = 4.327$, $p < 0.05$),<!-- p = 0.0220359 -->
and it explained 72.5% of the total variation in the rotational direction of *emc^AP6^* mutant hindgut ([@tbl:tbl3]).
These results suggested that the live cell chirality index directs the rotational direction of the hindgut in each individual embryo.
Based on these findings, we concluded that the enantiomorphic stats of cell chirality determines the LR asymmetry of the hindgut rotation.

<!--
0_metadata/meta0.md
0_metadata/meta1.md
1_abstract.md
2_introduction.md
3_procedures.md
4_results.md
5_discussion.md
6_figs.md
7_supplements.md
8_acknowledgements.md
9_references.md
-->
