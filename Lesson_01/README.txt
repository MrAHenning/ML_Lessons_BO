# Install conda notebook kernels
conda install -c conda-forge nb_conda_kernels

# Execute the following command to install dependencies
conda create -n lesson_01_env --file req.txt

# Activate the environment
conda activate lesson_01_env

# Run jupyterlab
jupyter-lab


# Work around:

conda install pandas
conda install numpy
conda install matplotlib
conda install seaborn
conda install scikit-learn
conda install -c conda-forge pandas-profiling
