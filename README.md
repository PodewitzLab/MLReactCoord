This repository contains a Jupyter Notebook for evaluating Causality and extraction a reaction coordinate using interpretable machine learning methods from molecular dynamics trajectories.

For details about the methods and an example, please see: https://doi.org/10.26434/chemrxiv-2024-nd20j

This repository is limited to a basic running example, due to the size of the trajectories. For the full dataset, please contact the owner of this repository or the corresponding authors.

To prepare the files, please extract the aligned trajectory archive and the individual trajectories to *two* separate empty folders and modify the appropriate paths in the notebook. 

To run the notebook, a python environment must be created:
```
conda create -c conda-forge -n Causality python=3.11.8 scikit-learn=1.4.1.post1 numpy=1.26.4 pandas=2.2.1 seaborn=0.13.2 statsmodels=0.14.1 scipy=1.12.0 pyemma=2.5.12 mdanalysis=2.7.0 matplotlib=3.8.3 dtreeviz=2.2.2

conda activate Causality
pip install skope-rules
```
