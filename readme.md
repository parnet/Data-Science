# Install the environment

use Anaconda, conda or miniconda to create a virtual environment in which every modul will be installed.
The installation process can be different on every machine. For us it was neccessary to install some module before installing interpretML. See the corresponding documentation for further installation instructions

```
conda create --name dsenv python=3.7
conda activate dsenv
conda install pandas
conda install seaborn
conda install numpy
conda install jupyter
conda install matplotlib 
conda install -c conda-forge pytorch
conda install -c omnia quadprog
conda install -c conda-forge cvxpy
conda install -c conda-forge shap
conda install -c conda-forge tensorflow
conda install -c anaconda scikit-learn 
pip install interpret

```

### launch notebook
the notebook is in the subfolder nbsrc

