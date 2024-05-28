# ERL-ProLiGraph
![Figure 1  Conceptual model of ERL-ProLiGraph](https://github.com/glorygeine/ERL-ProLiGraph_Main/assets/170915197/1ad99caa-be6c-4584-a323-40dbeea515d0)
![Figure 1  Conceptual model of ERL-ProLiGraph](https://github.com/glorygeine/ERL-ProLiGraph_Main/assets/170915197/1ad99caa-be6c-4584-a323-40dbeea515d0)

## Requirements
You'll need to install the following dependencies to run the codes.

*  keras
*  tensorflow
*  numpy
*  matplotlib
*  scikit-learn
*  rdkit
*  pconsc4
*  pytorch
*  torch-scatter
*  torch-sparse
*  torch-cluster
*  torch-spline-conv
*  torch-geometric
*  hhsuite
*  rdkit
*  ccmpred 

## Data
The data can be found here in the [datasets](https://github.com/hkmztrk/DeepDTA/blob/master/data/README.md).
*  The original Davis data and additional details can be accessed [here](http://staff.cs.utu.fi/~aatapa/data/DrugTarget/).
*  The original KIBA data and additional details can be accessed [here](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-017-0209-z).



## Train
We use 5-fold cross validation. <br>
Run the command: <br>
```sh
python training_5folds.py 0 0 0
```
The parameters represent dataset selection, GPU selection, and the specific fold (0, 1, 2, 3, 4).

## Test
This step involves making predictions using the models we trained and reproducing the experiments. <br>
Execute the command: <br>
```sh
python test.py 0 0
```
The parameters denote dataset selection and GPU selection.






