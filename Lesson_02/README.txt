# Install conda notebook kernels if not already done from lesson 1
conda install -c conda-forge nb_conda_kernels

# Execute the following command to install dependencies
conda env create -n lesson_02_env -f environment.yml

# Activate the environment
conda activate lesson_02_env

# Run jupyterlab
jupyter-lab

# Note: Large files need git "large file system" (lfs) support, and can be installed with
git install lfs

# Note: To compress and upload large files:
git lfs migrate importe --include="*.csv"

# Note: If large files are compressed, you can uncompress them with:
git lfs pull


# Work around by installing these libraries through conda or pip:
	- conda install pandas
	- conda install numpy
	- conda install matplotlib
	- conda install seaborn
	- conda install scikit-learn
	- conda install -c conda-forge pandas-profiling
