---
layout: page
title: Who is ready to make some science?
---
~ *Cave Johnson*

<hr color = '#fff'> 

### Education
![Nathan Anderson](pic.jpg){:height='378px' width='504px'}
BS in Applied Mathematics Texas A&M December 2019: 
Minor in Biology
<hr color = '#fff'>

### Research

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; I have been a researcher in the lab of Dr. Heath Blackmon (Dept. of Biology) since 2017. The lab has a broad focus in evolutionary biology but much of the research focuses on sex chromosomes, genome structure, and population genetics. My work has focused on phylogenetics and population genetic modelling, development of statistical methods for analysis of phylogenetics or other systems where individuals share a common origin. Namely, multi locus simulation of sexually antagonistic alleles under complex sex determination and recombination, statistical phylogenetic analysis of discrete and continuous trait evolution. I also lead a large scale experimental evolution project studying recombination rate adaptation to multilocus selection and changes in population structure. 

<hr color = '#fff'>

### Publications

**SAGA2.0** 

Armstrong A, N. W. Anderson, H. Blackmon. Inferring the potentially complex genetic architectures of adaptation, sexual dimorphism, and genotype by environment interactions by partitioning of mean phenotypes. Journal of Evolutionary Biology. 2019; 32:4 369-379. <https://doi.org/10.1111/jeb.13421>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<q style='display:inline-block; width:1000px; margin-left: 32px'>Genetic architecture fundamentally affects the way that traits evolve. However, the mapping of genotype to phenotype includes complex interactions with the environment or even the sex of an organism that can modulate the expressed phenotype. Line cross analysis is a powerful quantitative genetics method to infer genetic architecture by analyzing the mean phenotype value of two diverged strains and a series of subsequent crosses and backcrosses. However, it has been difficult to account for complex interactions with the environment or sex within this framework. We have developed extensions to line cross analysis that allow for gene by environment and gene by sex interactions. Using extensive simulations studies and reanalysis of empirical data, we show that our approach can account for both unintended environmental variation when crosses cannot be reared in a common garden and can be used to test for the presence of gene by environment or gene by sex interactions. In analyses that fail to account for environmental variation between crosses we find that line cross analysis has low power and high false positive rates. However, we illustrate that accounting for environmental variation allows for the inference of adaptive divergence, and that accounting for sex differences in phenotypes allows practitioners to infer the genetic architecture of sexual dimorphism.</q> 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Github](https://github.com/coleoguy/SAGA2)

**Ancestral Condition Test**

Anderson N. W, R. H. Adams, J. P. Demuth, H. Blackmon. Assessing the Impact of Continuous Traits on the Evolution of Discrete Traits: The Ancestral Condition Test. In Review.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<q style='display:inline-block; width:1000px; margin-left: 32px'>Analyses of the co-evolution of multiple traits has the potential to reveal the drivers and limits to biological evolution. A variety of methods are available to study the interaction between either two continuous traits or a discrete trait that impacts the evolution of a continuous trait. However, few methods are available to study the impact of a continuous trait on the evolution of a discrete trait. Here we present the ancestral condition test, a new comparative method that evaluates whether a binary trait tends to transition when a continuous trait has values more extreme than expected if both traits were evolving independently. This approach leverages ancestral state estimates of both the continuous and the binary trait to test whether extreme values of the continuous trait are associated with transitions in the binary trait, and to assess statistical significance.  We explore the robustness of our approach under a range of parameter values and patterns of trait evolution. We find that either a relatively strong contingency between the two traits or a large number of taxa is required to detect the underlying relationships reliably. Statistical power of the test is highest when the binary trait evolves unidirectionally, and we find that the false-positive rate remains acceptable for a bidirectionally evolving binary trait. In comparison to existing methods that might be employed, we show that the ancestral condition test has both higher power and a lower false-positive rate. The types of questions that this approach allows us to test are common in evolutionary biology and, unlike existing methods, the ancestral condition test incorporates the temporal order of transitions – moving a step closer to inferring causality rather than merely identifying correlation. An implementation of this test is distributed in the r package evobiR.
 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Poster](https://drive.google.com/open?id=1xWjilhFZ34JdqAH0Sq6QrtmwTxlXyfsW). <br> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Github](https://github.com/NW-Anderson/Ancestral-Condition-Test).&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

<hr color = '#fff'>

### Current Projects

**How much water is in the fountain of youth?** 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<q style='display:inline-block; width:1000px; margin-left: 32px'>Among species that have separate sexes, sex chromosomes are nearly ubiquitous and yet there are many unanswered question with regard to their evolutionary dynamics. XY sex chromosome systems are one of the most common methods of sex determination and have long interested researchers. Normally X and Y chromosomes differentiate over time as the Y chromosome decays. However, not all species experience this Y decay. The fountain of youth hypothesis suggests that imperfect sexual development and deleterious mutations on Y chromosomes may act together as a force to maintain homology between the X and Y. However, the viability of the fountain of youth hypothesis has not been well explored mathematically. Using both finite and infinite population genetic models we have shown that this process cannot completely eliminate sexually antagonistic selection – the force that is thought to lead to the decay of Y chromosomes. Using our modeling approach we are able to determine the parameter space under which the fountain of youth can and cannot preserve similarity between the X and Y chromosome. These results appear to support fountain of youth hypothesis by showing the limits to the canonical model of sex chromosome evolution and grant insight into the fitness effect of sex chromosome inversions.</q>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Poster](https://drive.google.com/file/d/1z3TgDcqhsfpzkswb43SNzQeYvo4kCNtR/view?usp=sharing). <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Github.](https://github.com/NW-Anderson/FOY)

**The Temporal Contingency Test: discovering correlation in the evolution of discrete traits**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<q style='display:inline-block; width:1000px; margin-left: 32px'>One of the central questions of evolutionary biology is how traits interact with each other over the course of evolution.  However, most of the methods available for understanding correlation or contingency in the evolution of discrete traits are based on detecting differences in the rate of transitions in one trait when it is associated with a specific state of the other trait.  These methods lead to several known problems.  We solve these problems by developing an approach that focuses on temporal contingencies in the transitions of discrete traits.  Our statistical approach can determine whether transitions in one trait lead to transitions in a second trait more quickly than would be expected under a model where the two traits evolve independently.</q>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Poster](https://docs.google.com/presentation/d/1pk9tAbmJ4eOlU8Y5A-5d2FPTz_BxWOH-tNLFeFKgdCU/edit?usp=sharing). <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Talk](https://docs.google.com/presentation/d/1Pwcj7orPf9Db11KuQuzQ_T8qJb2X_6rngYaSdsLDUtE/edit?usp=sharing). <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Github](https://github.com/NW-Anderson/TempCorr).

**Recombination Rate Response to Reductions in Population Size and Environmental Perturbations**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<q style='display:inline-block; width:1000px; margin-left: 32px'>

<hr color = '#fff'>

### Competitions

**On the Origin of Tacos**

**-Texas A&M Datathon 2019**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<q style='display:inline-block; width:1000px; margin-left: 32px'>Uncovering the evolutionary relationship between species is a central feature of evolutionary biology. In recent years, this work has been done using sequenced genomes, molecular clocks and phylogenetic comparative methods, however, prior to these advances researchers uncovered the hierarchical species relationships by comparing morphology. Given a dataset describing the tacos sold throughout the United States, we clustered these samples into morphological species based on ingredients and inferred the relationships between these species by constructing a morphological phylogeny using phylogenetic comparative methods. Furthermore, we were able to infer regional populations of our tacos using a kmeans clustering. Surprisingly, our morphological species seemed to be evenly spread throughout the regional populations, and certain species were not favored in any particular regions. Finally, we inferred the evolution of different morphological traits (different ingredients) along our phylogeny and were able to observe the species level evolution of taco types and to estimate the ancestral taco type at the root of our phylogenetic tree.</q>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[DevPost Project](https://devpost.com/software/on-the-origins-of-tacos?ref_content=contribution-prompt&ref_feature=engagement&ref_medium=email&utm_campaign=contribution-prompt&utm_content=contribution_reminder&utm_medium=email&utm_source=transactional#app-team). <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Github](https://github.com/MichelleJonika/datathon2019/tree/master/goldmansachs/final).

<hr color = '#fff'>

### [CV](https://docs.google.com/document/d/1x__x_N1p2K2cdQtj4fG9xxhNSBCTvy_BpAZppW_HBHY/edit?usp=sharing)


