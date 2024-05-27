---
title: Echovirus11 phylogeny
authors: "Sten de Schrijver"
dataset: "https://nextstrain.org/community/stends2001/Echovirus-11/3DPol?c=num_date"
date: "2024"
updated: "2024"
abstract: "This is a nextstrain narrative covering my work in Nextstrain thus far. Note that this analysis includes all complete genomes, and not any VP1-exclusive sequences. Let's start with looking at recent developments in the VP1 region. The brighter the dots are, the more recently they have been isolated. As you'll note, most of the sequences isolated between 2023 and 2024 are from the top clade."
---

# [VP1 tree coloured by country](https://nextstrain.org/community/stends2001/Echovirus-11/VP1?c=Country)
Appreciate the mixture of the origin of the sequences, especially in this larger top clade that contains sequences from France, Belgium and many other sequences. Interestingly, the sequences from Haiti form a very distinct group, as do the sequences from Ghana and Guatamala. It thus seems like the newest clade has only been found in Europe. Addtionally, note another large cluster from China, though this clade does include some sequences from Belgium and France as well.

# [VP1 classification into (sub)genotypes](https://nextstrain.org/community/stends2001/Echovirus-11/VP1?c=Genotype)
What I'm showing here is the proposed classifcation of (sub)genotypes, based on an analysis that I performed in R. I'm happy to see that in general terms, the tree built with NextStrain mostly agrees with what I've managed to produce in R, as evident by the (sub)genotypes clustering together per group. 

# [VP1 clade D5.9](https://nextstrain.org/community/stends2001/Echovirus-11/VP1?c=Genotype&f_Genotype=D5.9)
This largest group at the top I've called D5.9, although perhaps I can adjust the order of these clades, to call it D5.12.

# [VP1 clade D5.12](https://nextstrain.org/community/stends2001/Echovirus-11/VP1?c=Country&f_Genotype=D5.12&tl=none)
This is the second largest group, D5.12, the sequences in which were mostly isolated in China, though there's also a handful of sequences from Belgium, Bulgaria and France.

# [VP1 clades per age of patient](https://nextstrain.org/community/stends2001/Echovirus-11/VP1?branches=hide&c=Age&l=scatter&scatterX=Genotype&scatterY=Age)
What you see here is the age-distribution of the patients in which E11 of which clade was found. You'll notice that D5.9 is fairly widespread, while D5.10 has been found in surprisingly many neonates, and less so in 1-5 year olds (apologies for the odd ordering of the y-axis). The same goes for D5.5

# [VP1 clades per age of patient](https://nextstrain.org/community/stends2001/Echovirus-11/VP1?branches=hide&c=Country&l=scatter&scatterX=Genotype&scatterY=Age)
Though it should be noted that the patient data is available mostly for Dutch sequences. It is thus not unlikely that this represents a bias in the Netherlands of neonates being tested for E11.

# [3DPol colored by country](https://nextstrain.org/community/stends2001/Echovirus-11/3DPol)
This is a similar tree but then on the 3DPol region rather than the VP1. This tree as well, shows remarkable similarity to what I've found in R, which is great news! Note that similarly to the sequences based on VP1, there's a very clearly distinct clade for the Chinese sequences, for the Israeli sequences, and the sequences from Haiti. 

# [3DPol over time](https://nextstrain.org/community/stends2001/Echovirus-11/3DPol?c=num_date)
Similarly to the VP1 tree, there's a big clade that contains the most recently isolated sequences, namely those at the top. Note though, that there are some outliers to this.

# [3DPol groups per VP1 clades](https://nextstrain.org/community/stends2001/Echovirus-11/3DPol)
Now, here are the full genomes, phylogenetically studied based on 3DPol, but coloured by VP1 clades. This main most recent clade at the top predominantly contains sequences with a VP1 classified as D5.9, and you'll note that overall, the clusters in 3DPol link quite well with distinct VP1 clades.

# [Tangogram](https://nextstrain.org/community/stends2001/Echovirus-11/VP1:community/stends2001/Echovirus-11/3DPol)
This figure shows a similar conclusion.

# [Tangogram VP1: D5.9](https://nextstrain.org/community/stends2001/Echovirus-11/VP1:community/stends2001/Echovirus-11/3DPol?f_Genotype=D5.9)
Note that the vast majority of the VP1-D5.9 sequences are associated with the one major clade of 3DPol, though there are some exceptions.

# [Tangogram VP1: D5.12](https://nextstrain.org/community/stends2001/Echovirus-11/VP1:community/stends2001/Echovirus-11/3DPol?f_Genotype=D5.12&tl=none)
Similarly, the sequences classified as VP1-D5.12 show very clear association with a distinct 3DPol clade.

# [Tangogram VP1: D5.10](https://nextstrain.org/community/stends2001/Echovirus-11/VP1:community/stends2001/Echovirus-11/3DPol?f_Genotype=D5.10&tl=none)
Now this is an interesting VP1 clade, VP1-D5.10, which is associated with two distinct 3DPol clades, with a single exception.

# [Tangogram](https://nextstrain.org/community/stends2001/Echovirus-11/VP1:community/stends2001/Echovirus-11/3DPol)
Overall, the classification of sequences based on VP1 coincides with that based on 3DPol quite nicely.

# [What's next]
What I'll want to focus on next includes the following points:
- Determine which mutations allow grouping into certain clades/branches. Having such a system will make it much easier to put in the VP1 sequences too, of which we have a lot, including much clinical data.
- Include VP1 sequences into the VP1 - tree
- Perform statistical analyses on the VP1 tree
- Dermine classification of 3DPol sequences (into genotypes)
- Find recombination breakpoints across the genome, and perhaps even inside 3DPol
- Ideally, we'd be able to setup a VP1 and 3DPol build which would allow one to insert an E11 sequence, and get an output saying which VP1 genotype it belongs to and which 3DPol genotype it belongs to. 
