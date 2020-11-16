# multigeneblast_gk
A fork of the MultiGeneBlast (Medema et al. 2013) multigeneblast.py script for comparison/search of syntenic secondary metabolite cluster similarities. Contains changes to the following: calculation of query coverage is now correctly normalised to length of the query sequence, it is now possible to calculate scores for single matches (by default at least two syntenic hits were required for detection of cluster similarity).

USAGE: drop it into the MultiGeneBlast 1.13 directory and use in place of multigeneblast.py. The additional flag for single matches is '--singles y'.
