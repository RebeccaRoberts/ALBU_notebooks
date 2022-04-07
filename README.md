# ALBU_notebooks

## Suplementary material for Appendices
These are some of the notebooks that I have used as part of my PhD studies. They can be used as supporting documentation for my appendices as follows:

### Appendix A
##### polya_appendix_A.ipynb
A notebook showing a simple 3 node graphical model, which is similar to one branch of the word-topic side of Latent Dirichlet Allocation (LDA). Here the pproximation from the Polya to the Dirichlet distribution is described and plotted for the 2D case.
##### hierachical_sampling_for_dirichlet_polya_Appendix_A.ipynb
A notebook showing the hirachical sampling to process to calculate the local message from a Polya to a Dirichlet distribution (described in Section A.1.4.2) for the 3D and 2D case.

### Appendix C
##### experiment_structure.ipynb 
A notebook showing how experiments are saved and how hyperparameters of an experiment can be recovered. This cannot be run in isolation since it requires the experiment files etc. It also shows how the convergence plots are created from the experiment files.

### Appendix E
##### dirichlet_approximation_Appendix_A.ipynb
Here we compare the approximate messages from a Polya to Dirichlet node as calculated by the VMP (VB), ALBU and hierachical sampling.

## Suplementary material for testing the VMP algorithm
##### VMP.ipynb 
In this notebook, we extract just the necessary code from our codebase and lda wrapper package to run VMP on the LDA graphical model. We also show how the text pre-processing is performed and how coherence metrics are plotted.
