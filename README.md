# Binding Affinity Prediction with ML-Based Docking

Virtual screening of EGFR binders by understanding what binding free energy is and how we can leverage it. Using datasets of 2D molecules, we will develop predictive models to assess the affinity against EGFR protein. We will build concepts on how to use molecular docking to predict the binding affinity of a ligand to a protein and the concept of **active learning** to improve the performance of our models by utilizing the docking as an oracle.

Please ensure all dependencies are installed.

You can install those dependencies by

mamba env create -n lab2 -f env.yml

conda activate lab2

For visualization of the docking results, you need to install py3Dmol by running the following command:

pip install py3Dmol

For better Active learning performance, you can install modAL by running the following command:

pip install modAL-python
