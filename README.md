### Phylogenetics and Genomic Language Models

Exploring the use of genomic lanuage models (gLMs) for predicting sequences across species. Please see [the project description](project_description.pdf) for further background, methods and results.

Firstly, I investigate the zero-shot transfer performance of a model from Albors et al. [[1]](#1), which makes predictions based on combined intra and inter-species (multiple sequence alignment (MSA)) information. (Section 2 and Figures 2 & 3, [code here](/notebooks/PhyloGPN.ipynb)).
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CatherineFelce/phylogenetic-gLMs/blob/main/notebooks/PhyloGPN.ipynb)


I then propose a novel approach to identifying regions of evolutionary interest via analysis of LM vs MSA entropy, and present a proof-of-concept experiment (Section 3, Figures 4-9, [code here](/notebooks/entropyt_analysis.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CatherineFelce/phylogenetic-gLMs/blob/main/notebooks/entropy_analysis.ipynb). I suggest that the separate use of alignment-blind language models and known MSAs could contribute to our understanding of how different genomic regions evolve. 


This project was undertaken for CS159, instructor Professor Yisong Yue, in summer term of 2025.

## References
<a id="1">[1]</a>  Albors, C., Canal Li, J., Benegas, G., Ye, C., & Song, Y. S. (2025).  
*A Phylogenetic Approach to Genomic Language Modeling*.  
arXiv:2503.03773. https://arxiv.org/abs/2503.03773
