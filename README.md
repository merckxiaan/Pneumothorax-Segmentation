This repository houses my attempt at creating a computervision model for the Kaggle SIIM-ACR Pneumothorax Segmentation competition.

For each `.ipynb`, there's a autogenerated `.jl` file which contains all the code cells which start with `#export`.

Currently, Flux(/Zygote) throws an error because of array mutation. I'm not sure where this mutation actually occurs.
