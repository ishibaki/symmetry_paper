# Results

## A logistic model significantly explained the correlation between cell chirality and the LR direction of hindgut rotation

The *Drosophila* hindgut is first formed as a bilaterally symmetric invagination whose anterior part curves ventrally at early stage 12 ([@fig:fig1]A most left panel) [@Hozumi2006].
Then, it gradually rotates counterclockwise 90 degrees as a view from the posterior ([@fig:fig1]A, middle two panels).
Consequently, this rotation makes the hindgut curved towards the right at the end of stage 13 ([@fig:fig1]A, most right panel).
The hindgut epithelium has a typical apical-basal polarity, and the inner surface of the hindgut corresponds to the apical surface.
Before the rotation of the hindgut, cell chirality of the hindgut epithelial cells is detected in the shape of their apical surface, as the frequency of cell boundaries that slant left or right with respect to the anterior-posterior axis of the hindgut tube shows deviations according to the genetic conditions [@Ishibashi2019].
For example, cell-boundaries slanting to the left appeared more often than that of the right in wild type ([@fig:fig1]B, left).
However, such LR bias found in the angle of cell boundaries are dissolved after the completion of the hindgut rotation ([@fig:fig1]B, right).
To quantitatively analyze the cell chirality, "chirality index" was formulated previously [@Ishibashi2019].
The apical cell boundaries were visualized, and the origin of two-dimensional coordinate corresponding the anterior-posterior and left-right axes are placed on a vertex ([@fig:fig1]C most left).
The cell boundaries exist in the first and third quadrants (shown in orange) and the second and fourth quadrants (shown in blue) are defied as Right (orange lines) and Left (blue liens), respectively ([@fig:fig1]C left and middle).
Then, the total numbers of Right and Left were represented by N-Right ($N_{R}$) and N-Light ($N_{L}$), respectively, and the cell chirality index was calculated by a formula, $\frac{N_{R} - N_{L}}{N_{R} + N_{L}}$ ([@fig:fig1]C, right).

We previously showed that the chirality index strongly correlated with the ratio of the normal hindgut laterality in the *Drosophila* embryos with various genotype [@Ishibashi2019].
To investigate a causal association between the cell chirality and the direction of the hindgut rotation, we here analyzed the mathematical characteristics of the correlation between the chirality index and the rotational direction of the hindgut.
We scored the rotational direction of the hindgut as a "laterality score", in which the hindgut of normal LR asymmetry, non-laterality (bilateral symmetry), and inverse LR asymmetry was scored 1, 0.5, and 0, respectively ([@fig:fig2]A).
The mean of the laterality score was calculated in embryos with each genotype ([@fig:fig2]B, left).
Besides the genetic conditions analyzed in the previous study, we examined ten different genetic conditions in total to study the correlation between the chirality index and the mean of the laterality score ([@fig:fig2]B) [@Ishibashi2019].
As the newly added conditions, double mutant embryos of *da^10^* and *emc^AP6^* (*da^10^; emc^AP6^*) were analyzed ([@fig:fig2]B).
Our previous analysis revealed that *da* mutation suppresses the LR defects of the hindgut in *emc* mutant, because *emc* mutant induces the LR defects though the hyper-activation of *da* [@Ishibashi2019].
Additionally, embryos overexpressing *UAS-MyoIC*, which is known to have a sinistral activity of the LR asymmetric development, in the hindgut epithelium were examined ([@fig:fig2]B) [@Hozumi2008; @Okumura2015].

We fitted the logistic model (dotted line) with the chirality index as an explanatory valuable and the mean of the laterality score as an objective variable ([@fig:fig2]B).
The chirality index significantly explained the mean of laterality score
([すみません，図のp-valueが間違ってました]{.comment-start author="Tomoki Ishibashi" date="2020-09-20T00:01:08Z"}Quasibinomial generalized linear model (GLM), two-tailed t-test[]{.comment-end}, $p < 0.001$) ([@fig:fig2] B, [@tbl:tbl1]).
<!-- Intercept: t(8) = -4.042, p = 0.003723
Chirality Index: t(8) = -5.992, p = 0.000326 -->

## Chirality index predicts the LR directions of future hindgut rotation in live embryos

Considering that cell chirality appears before the hindgut rotation, the significant correlation between the chirality index and the mean of laterality score suggested that the average of cell chirality determines the LR direction of the hindgut rotation in each embryo.
In this case, the chirality index in each live embryo should predict the left or right directionality of the future hindgut rotation afterwards.
To test this possibility, we developed a new procedure to obtain the chirality index in the hindgut of live embryos and then determine the subsequent LR directionality of the hindgut rotation.
In this system, the apical cell boundaries of the hindgut epithelium were visualized in live embryos at [early]{.insertion author="Tomoki Ishibashi" date="2020-09-20T00:06:34Z"} stage 12 under a confocal laser microscope, and these embryos were continuingly cultured another three hours ([@fig:fig3]A).
At that point, the rotation of the hindgut was completed under these conditions in wild-type ([@fig:fig3]A right).
The chirality index obtained from this procedure was designated as "live chirality index," and the laterality score of each embryo was marked 1, 0.5, and 0, as the hindgut subsequently showed normal LR asymmetry, non-laterality (bilateral symmetry), and inverse LR asymmetry, respectively.

To investigate whether the live chirality index directs the rotational direction of the hindgut, we conducted a statistical correlation analysis between the live chirality index and laterality score of each embryo.
We found that the LR-randomization phenotypes of *emc^AP6^* homozygote were appropriate for this purpose, because the hindgut of these embryos shows normal and inverse LR asymmetry as well as non-laterality, whereas the overall structure of the hindgut is virtually normal besides the defects in its LR asymmetry [@Ishibashi2019].
To evaluate the consistency between the chirality indexes obtained from fixed and live embryos, we analyzed the mean of live chirality indexes in wild-type and *emc^AP6^* homozygous embryos before the hindgut rotation.
The [mean]{.insertion author="Tomoki Ishibashi" date="2020-09-20T00:12:02Z"} live chirality indexes of wild-type and *emc^AP6^* homozygous embryos were $-0.12 \pm 0.04$ and $-0.02 \pm 0.03$, respectively, which were very similar to those of fixed embryos as reported before (wild-type, $-0.11 \pm 0.03$; *emc^AP6^* homozygote, $0.01 \pm 0.02$) [@Ishibashi2019].
We found that each individual embryo of *emc^AP6^* homozygote showed a broad range of live chirality indexes as compared with that of wild-type, although the mean values of live chirality indexes were not significantly different between in the *emc^AP6^* mutants and the wild-type (Two-tailed t-test, $p = 0.069217$) ([@fig:fig3]B) [p-valueを修正済です]{.comment-start author="Tomoki Ishibashi" date="2020-09-20T00:42:12Z"}[]{.comment-end}.
<!--
Live cell chirality:
    CS       -0.117237 +- 0.035853
    emcAP6   -0.022627 +- 0.031554
Fixed cell chirality:
    CS       -0.108681 +- 0.025608
    emcAP6    0.011422 +- 0.015463
-->

Given that the live chirality index agrees well with the chirality index in the fixed embryos, we next conducted a statistical correlation analysis between the live chirality index and laterality score of each *emc^AP6^* mutant embryo obtained after continuing culture.
We fitted the logistic model ([solid]{.insertion author="Tomoki Ishibashi" date="2020-09-20T00:46:56Z"}[dotted]{.deletion author="Tomoki Ishibashi" date="2020-09-20T00:46:56Z"} line) with the live chirality index as an explanatory variable and the laterality score of each embryo as an objective variable and found that live cell chirality before the hindgut rotation significantly explained the rotational direction of the hindgut
(Quasibinomial GLM, two-tailed t-test, $p < 0.01$; [@fig:fig3]C; [@tbl:tbl2]).
Importantly, the logistic regression model [(dotted line)]{.insertion author="Tomoki Ishibashi" date="2020-09-20T00:47:13Z"} obtained the fixed embryos of various genetic conditions as described in [@fig:fig2] significantly fitted the data obtained from each livin *emc^AP6^* mutant embryo
(Quasibinomial GLM, likelihood ratio test, $\chi^{2}_{1} = 4.327$, $p < 0.05$),<!-- p = 0.0220359 -->
and it explained 72.5% of the total variation in the rotational direction of *emc* mutant hindgut ([@tbl:tbl3]).
These results suggested that the live chirality index directs the rotational direction of the hindgut in each embryo.
Based on these findings, we concluded that the enantiomorphic states of mean cell chirality determine the LR asymmetry of the hindgut rotation.

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
9_acknowledgements.md
-->
