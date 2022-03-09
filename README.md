# Simple JS implementation of ODS

The objective digital stain (ODS) is represented by a distribution of points on a two-dimensional (2D) image, which reflects the information structure inside a DNA/RNA sequence. But from where do we get the x-axis and y-axis of each point? In order to build an ODS, a scanner that uses sliding windows must be developed first.The x-axis values and the y-azia values for a point are calculated from the content of a sliding window. One value for the x-axis is computed using an algorithm called self-sequence alignment, and the y-axis value for a point is computed using the frequency of C plus G letters from the sliding window. Since the content of each sliding window provides a point on the image, a visible shape starts to reveal itself.

In turn, the shape of the distribution pushes the association of the method with a kind of “digital stain,” thus safely establishing the name of the method. In the past, ODSs were simply called “DNA patterns”. On ODSs, the information content (IC) is represented vertically on the y-axis and the frequency of different letters is represented horizontally on the x-axis. The overall idea surrounding this method is that similar distributions of two or more DNA/RNA sequences may show similar functions. Interestingly, dissimilar
DNA/RNA sequences may show similar ODSs. This intriguing proprietary has been demonstrated repeatedly over time. The first observation was made in 2012 in the journal [BMC Genomics](https://bmcgenomics.biomedcentral.com/articles/10.1186/1471-2164-13-512). There, different ODS patterns have been shown for eukaryotic gene promoters that indicate several generic classes of promoters (more than 10 classes of promoters in eukaryotes). Moreover, in 2013 in [the same journal](https://bmcgenomics.biomedcentral.com/articles/10.1186/1471-2164-14-278), a correlation was made between chromosomal territories and ODS patterns shown by gene promoters. More recently, in 2015, [a publication](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4574929/) in the [journal PLoS ONE](https://doi.org/10.1371/journal.pone.0137950) showed the connection between ODSs of promoter sequences and the genes associated with type 1 and 2 diabetes. This latest publication showed more clearly that ODSs are able to link the DNA sequence characteristics to different biological functions.

Live demo: https://gagniuc.github.io/Simple-JS-implementation-of-Objective-Digital-Stains/

# Screenshot
<kbd><img src="https://github.com/Gagniuc/Simple-JS-implementation-of-Objective-Digital-Stain-ODS-/blob/main/Objective%20Digital%20Stains.PNG" /></kbd>


# Implementations - other
The Objective Digital Stains are also implemented in other languages, from which entire customised applications can be made.

In Java Script:
https://github.com/Gagniuc/Objective-Digital-Stains

In PHP:
https://github.com/Gagniuc/Objective-Digital-Stains-in-PHP

In VB6:
https://github.com/Gagniuc/PromKappa-3.0-Objective-Digital-Stains-in-VB6

# Info on ODSs
 Please read more about DNA patterns (aka Objective Digital Stains) here:
 
 Eukaryotic genomes may exhibit up to 10 generic classes of gene promoters: 
 https://bmcgenomics.biomedcentral.com/articles/10.1186/1471-2164-13-512
 
 and 
 
 Gene promoters show chromosome-specificity and reveal chromosome territories in humans:
 https://bmcgenomics.biomedcentral.com/articles/10.1186/1471-2164-14-278
 
 and
 
 Algorithms in Bioinformatics: Theory and Implementation:
 https://www.wiley.com/en-ag/Algorithms+in+Bioinformatics%3A+Theory+and+Implementation-p-9781119697961
 

# References

- <i>Gagniuc P.A. and Ionescu-Tirgoviste C.: Eukaryotic genomes may exhibit up to 10 generic classes of gene promoters. BMC Genomics 2012, 13:512.</i>

- <i>Ionescu-Tîrgovişte C*, Gagniuc PA*, Guja C (2015) Structural Properties of Gene Promoters Highlight More than Two Phenotypes of Diabetes. PLoS ONE 10(9): e0137950.</i>

- <i>Gagniuc P.A. and Ionescu-Tîrgovişte C. Gene promoters show chromosome specificity and reveal chromosome territories in humans, BMC Genomics 2013, 14:278.</i>

- <i>Paul A. Gagniuc. Algorithms in Bioinformatics: Theory and Implementation. John Wiley & Sons, Hoboken, NJ, USA, 2021, ISBN: 9781119697961.</i>
