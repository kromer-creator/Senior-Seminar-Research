# Senior-Seminar-Research
## What can eigenvalues teach us about quantum fields?

For my math Senior Seminar project, I am researching the spectra of eigenvalues generated in many different ways. This is inspired by a paper entitled "Finite Quantum Chaos" written by Audrey Terras. I began this research in fall 2021 and will be writing a 10-page expository paper, which will be completed by spring 2022. 

### Eigenvalue & Graph Generation: 
* This is where I am storing all of my code to generate different eigenvalues
* I create eigenvalues from the adjacency matrices of Cayley graphs of cyclic permutations, random adjacency matrices, random symmetric matrices, Uniform, and Poisson distributions

### Statistical_Analysis:
* Contains a collection of functions for statistical analysis on these eigenvalues, such as mean, standard deviation, etc.
* Displays the results from this analysis and contains observations made

#### [Google Drive Folder of Data Collection](https://drive.google.com/drive/folders/1Xgm2uUiUob-MiAytpJ6Yp9cBu1OCzeBp?usp=sharing)
* Contains multiple histograms from each eigenvalue generator

### Tools:
* Jupyter Notebook
* Python & Numpy
* SageMath

### Usage Instructions: 
* In either code file: If you try to run the code, you must run the first block before you can run the other blocks. They are dependent upon functions in the first blocks.
* If you do not have Jupyter Notebook on your computer, you can run this code from a Google colab notebook online. There is **1 exception** to this: 
  * If you want to run one of the Cayley graph blocks in Eigenvalue & Graph Generation, you must have SageMath installed on your computer. Furthermore, you must configure Jupyter Notebook on your computer to be compatible with SageMath.
