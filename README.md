# McCord.chat

A conversational assistant for the general public and the research community with the CORD-19 dataset and the research on COVID-19.

## Components, resources & subprojects

_Each heading possibly in separate repos._

1. CORD-19: full text + metadata as JSON objects, no figures, publications id-ed and networked by allen-nlp.  
   1. Collect PDFs to create datasets for supervised, semi-supervised, and unsupervised training of (the distributed and dynamically integrated components) of a _"paper digester"_.  The goal is to create a _multi-modal transformer_ for the digestion of any scientific paper and document into operational hierarchical inhomogeneous-network format.  PDFs will be converted to images so that the model can learn to use computer vision as the sole input.  
   2. Explore [graph neural networks](https://www.google.com/search?q=graph+neural+network) for the true-Rumelhart PDP representation of knowledge bases with distributed multi-modal representation and identificiation of "concepts" as the compositional and hierarchical units of human (scientivic) knoweledge.  
2. Conversational baseline on Rasa.  
   1. 
