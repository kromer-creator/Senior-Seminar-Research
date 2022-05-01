# Senior-Seminar-Research
## What can eigenvalues teach us about quantum fields?

For my math Senior Seminar project, I researched the spectra of eigenvalues generated in many different ways. This is inspired by a paper entitled "Finite Quantum Chaos" written by Audrey Terras. The general motivation is to discover connections between various branches of mathematics through studying the spectra of eigenvalues. This project includes 2 presentations and a research paper, which were completed over the course of my senior year, Fall 2021-Spring 2022. The research portion of this project was completed using code written in Jupyter notebooks.

## My Paper: Mathematical Connections through Eigenvalue Spacings
* File: Senior_Seminar_Paper.pdf
* This 15-page paper thoroughly explains the motivation for my research, what my research is, how it was done, and analysis of findings. 

## Code Notebooks

### Eigenvalue & Graph Generation: 
* This is where I am store all of my code to generate different eigenvalues and other number spectra.
* I create eigenvalues from the adjacency matrices from n-gons, random adjacency matrices, and random symmetric matrices (normal and uniformly populated).
* Also model spectra of Uniform and Poisson distributions
* Histograms generated in this file

### Statistical_Analysis:
* Contains a collection of functions for statistical analysis on these eigenvalues, such as mean, standard deviation, etc.
* Displays the results from this analysis and contains observations made

## Presentations

### Graphs and Eigenvalue Distributions:
* These are slides from my first presentation on my work (March 2022). It roughly covers the first half of material, focusing on the mechanics of the research itself and briefly introducing observations.

### Mathematical Connections through Eigenvalue Spacings:
* These are slides from my second presentation (April 2022). It covers a more sophisticated motivation for my research, including background on the mathematical branches that may be connected through the study of eigenvalue spacings. It also discusses more observations.

## Other Information:

### Access "Finite Quantum Chaos" by Audrey Terras: 
* Link: https://www.tandfonline.com/doi/pdf/10.1080/00029890.2002.11919846?needAccess=true
* Requires access, either through university credentials, purchase, or membership
* Alternatively, access Dr. Terras' lecture notes on the topic: ["Finite Models for Arithmetical Quantum Chaos"](https://mathweb.ucsd.edu/~aterras/newchaos.pdf)

### Tools:
* Jupyter Notebook
* Python & Numpy
* SageMath
* LaTeX (for presentations and paper), written on [Overleaf](https://overleaf.com)

### Usage Instructions: 
* If you do not have Jupyter Notebook on your computer, you can run this code from a Google colab notebook online. There is **1 exception** to this: 
  * If you want to run one of the Cayley graph (n-gon) blocks in Eigenvalue & Graph Generation, you must have SageMath installed on your computer. Furthermore, you must configure Jupyter Notebook on your computer to be compatible with SageMath.
