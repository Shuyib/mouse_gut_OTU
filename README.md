This analysis is an additional step of the [ebioKit tutorials](http://77.235.253.122/tutorials/courses/16s-metabarcoding-analysis/) to visualize the results of 16S metabarcoding using unsupervised learning techniques such as t-distributed stochastic neighbor embedding(t-SNE) and Principal component analysis(PCA) -- You can even use a barplot to find the answer to this question or a frequency table.

Read more about MiSeq SOP the Schloss Lab uses to process their 16S rRNA gene sequences that are generated using Illumina's MiSeq platform using paired end reads [here.](https://www.mothur.org/wiki/MiSeq_SOP)

---
Setting up your environment
* Download Anaconda for your operating system for Python 3 [anaconda](https://www.anaconda.com/download/)
* Create a conda environment like mine:

  `conda env create -f environment.yml`
  This creates an environment called py35. Activate it with this command in your terminal

  `source activate py35`

* In your terminal, in the directory where you cloned this repository. Run this command

  `jupyter notebook otu_data_viz.ipynb`
    
---

A codebook will be provided for the .csv file: I encourage you to go through the exercise [here.](http://77.235.253.122/tutorials/courses/16s-metabarcoding-analysis/) to generate the **0.16.cons.taxonomy.csv dataset**. Which was created by processing .fastq files obtained from *Mus musculus* with [Mothur](https://www.mothur.org/).


 