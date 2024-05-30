---
title: Echovirus11 phylogeny
authors: "Sten de Schrijver"
dataset: "https://nextstrain.org/community/stends2001/E11/VP1"
date: "2024"
updated: "2024"
abstract: "This is a nextstrain narrative covering my work in Nextstrain thus far. Note that this analysis includes all complete genomes, and not any VP1-exclusive sequences. What we currently see is a tree on the complete genomes, with the currently used classification, a few sequences at the bottom I haven't called a genome given that these are single sequences that make up a clade."
---


# [VP1 tree coloured by time](https://nextstrain.org/community/stends2001/E11/VP1?c=num_date)
Let's start with looking at recent developments in the VP1 region. The brighter the dots are, the more recently they have been isolated. As you'll note, most of the sequences isolated between 2023 and 2024 are from the top clade.

# [VP1 tree coloured by country](https://nextstrain.org/community/stends2001/E11/VP1?c=Country)
Appreciate the mixture of the origin of the sequences, especially in this larger top clade that contains sequences from France, Belgium and many other sequences. Interestingly, the sequences from Haiti form a very distinct group, as do the sequences from Ghana and Guatamala. It thus seems like the newest clade has only been found in Europe. Addtionally, note another large cluster from China, though this clade does include some sequences from Belgium and France as well.

# [VP1 classification into subgenotypes](https://nextstrain.org/community/stends2001/E11/VP1?c=Subgenotype)
What I'm showing here is the proposed classifcation of (sub)genotypes, based on an analysis that I performed in R, and later in Nextstrain itself, through specifying which mutations make for classification into which subgenotype. Note that some sequences have not been classified yet, because they have been too difficult to do so.

# [VP1 clade D5.9](https://nextstrain.org/community/stends2001/E11/VP1?c=Subgenotype&f_Subgenotype=D5.9)
This largest group at the top I've called D5.9, although perhaps I can adjust the order of these clades, to call it D5.12.

# [VP1 clade D5.12](https://nextstrain.org/community/stends2001/E11/VP1?c=Subgenotype&f_Subgenotype=D5.12&tl=none)
This is the second largest group, D5.12, the sequences in which were mostly isolated in China, though there's also a handful of sequences from Belgium, Bulgaria and France.

# [3DPol colored by country](https://nextstrain.org/community/stends2001/E11/3DPol?c=Country&tl=none)
This is a similar tree but then on the 3DPol region rather than the VP1. This tree as well, shows remarkable similarity to what I've found in R, which is great news! Note that similarly to the sequences based on VP1, there's a very clearly distinct clade for the Chinese sequences, for the Israeli sequences, and the sequences from Haiti. 

# [3DPol over time](https://nextstrain.org/community/stends2001/E11/3DPol?c=num_date&tl=none)
Similarly to the VP1 tree, there's a big clade that contains the most recently isolated sequences, namely those at the top. Note though, that there are some outliers to this.

# [3DPol genotypes](https://nextstrain.org/community/stends2001/E11/3DPol?c=Genotype&tl=none)
Similarly to VP1, I've classified 3DPol into genotypes.

# [3DPol E9 sequence](https://nextstrain.org/community/stends2001/E11/3DPol?c=Genotype_VP1&f_Genotype_VP1=E9&tl=none)
While the E9 sequence in the VP1 tree is an actual outgroup, in the 3DPol tree, it clusters closely with some E11 sequences.

# [Tangogram](https://nextstrain.org/community/stends2001/E11/VP1:community/stends2001/E11/3DPol?c=Subgenotype)
Recombination!

# [Tangogram VP1: D5.9](https://nextstrain.org/community/stends2001/E11/VP1:community/stends2001/E11/3DPol?c=Subgenotype&f_Genotype_VP1=D5.9)
Note that the vast majority of the VP1-D5.9 sequences are associated with the one major clade of 3DPol, though there are some exceptions.

# [Tangogram VP1: D5.12](https://nextstrain.org/community/stends2001/E11/VP1:community/stends2001/E11/3DPol?c=Subgenotype&f_Genotype_VP1=D5.12&tl=none)
Similarly, the sequences classified as VP1-D5.12 show very clear association with a distinct 3DPol clade.

# [Tangogram VP1: D5.10](https://nextstrain.org/community/stends2001/E11/VP1:community/stends2001/E11/3DPol?c=Subgenotype&f_Genotype_VP1=D5.10&tl=none)
Now this is an interesting VP1 clade, VP1-D5.10, which is associated with two distinct 3DPol clades, with a single exception.

# [Tangogram](https://nextstrain.org/community/stends2001/E11/VP1:community/stends2001/E11/3DPol?c=Subgenotype)

# [What's next]
What I'll want to focus on next includes the following points:
- Include VP1 sequences into the VP1 - tree
- Perform statistical analyses on the VP1 tree
- Find recombination breakpoints across the genome, and perhaps even inside 3DPol
- Ideally, we'd be able to setup a VP1 and 3DPol build which would allow one to insert an E11 sequence, and get an output saying which VP1 genotype it belongs to and which 3DPol genotype it belongs to. 