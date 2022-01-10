# despota
DEndogram Slicing through a PermutatiOn Test Approach: R code

DESPOTA (**DE**ndogram **S**licing through a **P**ermutati**O**n **T**est **A**pproach) is a novel approach exploiting permutation tests in order to automatically detect a partition among those embedded in a dendrogram. Unlike the traditional approach, DESPOTA includes in the search space also partitions not corresponding to horizontal cuts of the dendrogram.

The output of hierarchical clustering methods is typically displayed as a dendrogram describing a family of nested partitions. However, the exploitable partitions are usually restricted to those relying on horizontal cuts of the tree, missing the possibility to explore the whole set of partitions housed in the dendrogram. We introduced an algorithm, DESPOTA, exploiting the methodological framework of permutation tests, that permits a partition to be automatically found where clusters do not necessarily obey the above principle. Our solution adapts to every choice of the distance metric and agglomeration criterion used to grow the tree.

You can find more information on **DESPOTA** [following this link](http://domenicovistocco.it/en/dv-blog/despota-page/).

At the moment there is no official code for Despota. The current version of the code is not very fast in case of big data, but it works. Here a small tutorial including the main functions and some auxiliary plotting functions is available.
 
I would be very glad of having any (positive as well as negative) feedback if you use DESPOTA on your data. Moreover, let me known in case you are interested to start a collaboration on the topic.
