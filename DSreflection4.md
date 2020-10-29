# Data Science and The Genome 

Genomic data science is a field that utilizes statistics and data science to better understand and study DNA and the genome. An emerging sect of this field is the application of machine learning to CRISPR, a tool used for gene editing. CRISPR works by employing RNA and Cas9 enzymes (molecular scissors) to alter a sequence of nucleotides, which will subsequently activate or deactivate a gene. However, the main issue with the Cas 9 enzyme is that it is difficult to correctly place it along the genome, even if it is within a gene. Further, it can be challenging to identify the best place to remove a segment of DNA in order to turn-off a specific gene. This raises the question: what place in the genome is best suited to maximize the desired effect? Recently, it has been found that machine learning is particularly well-equipped to best answer this question. 

Supervised machine learning is an example of machine learning that can be used to quantify how effective CRISPR is at a specific point on a gene. This model entails an RNA sequence guide that contains approximately 30 nucleotides that subsequently produces data on how much of that gene was removed. Thus, the data produced from this model is the pairs of inputs (RNA sequences) and outputs (how much of the gene was removed). Comparatively, unsupervised learning takes a more complex approach that can be challenging to interpret. In this model, data for genes is clustered according to a predetermined quality, and then a metric is chosen to define similarities between this data. Based on that metric, the genes are aggregated into clusters. This method is different from supervised learning in that the model is only given an input and does produce an output; patterns seem to be the focus of unsupervised learning. 
 
Microsoft Research’s current tool provides an ordered list of the top places one might cut a specific gene in order to maximize its removal and subsequent deactivation. In addition to this, recent developments have led to a new machine learning method that will indicate the potential for disruption of the genome if the gene is cut in that previously identified place. This will allow for more informed decision making on whether or not to make the cut in a gene, comparing the efficiency of removal of the gene and how much this removal might disrupt the genome as a whole. However, this does present a significant challenge to the supervised machine learning method, as the entire genome must be scanned in order for this method to be fully accurate. 

Overall, machine learning and genomic data science has a large potential to benefit genetics and the health field in general. In medicine, there is a large emphasis on predictive measures, which plays to the strength of machine learning in predicting outcomes based on thoroughly analyzed data. Thus, health and medicine is a field in which machine learning can work extremely well, reaping numerous benefits. Its ability to make sense of complex data by constructing models will certainly pave the way for new developments in the understanding of the human genome. 


## References 

Navarro, F.C.P., Mohsen, H., Yan, C. et al. Genomics and data science: an application within an umbrella. Genome Biol 20, 109 (2019). 

Peltz, M. (2019, January 16). Machine Learning Meets Genome Editing. 

Saey, T. H. (2020, October 10). Explainer: How CRISPR works. Science News for Students. 
