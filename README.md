# Model Validation on EOS4TCC

## Repository organisation
The repository is organised in folders:
- '/notebooks' contains the jupyter notebooks where most of the work is being developed
- '/data' contains all the .csv files. Model predictions are obtained outside this repository and saved in this folder. 
- '/src' contains important functions I will re-use throughout the repository, to avoid typing them each time
- '/figures' contains the plots I have produced during the model validation process
- 'requirements.txt' lists all the required packages to run the notebooks in this repository.
  
This repository run predictions on 1000 clean and standardised molecules using Ersilia Model BayeshERG with EOS model ID: eos4tcc

BayeshERG is a robust, reliable and interpretable deep learning model for predicting hERG channel blockers. 

The BayeshERG is developed with the python v3.6 and following packages:dgl, pytorch, and rdkit.

**CITATION**

[Original Authors](https://academic.oup.com/bib/article/23/4/bbac211/6609519?login=false)

[Ersilia Model Hub](https://github.com/ersilia-os/ersilia/blob/master/CITATION.cff)

## License
All the code in this repository is licensed under a GPLv3 License.
