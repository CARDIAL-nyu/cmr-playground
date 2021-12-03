# Golden-Angle Cardiac MRI Sample Notebooks


## Jupyter Notebooks
 - **1. [Single Coil Demo](https://github.com/CARDIAL-nyu/cmr-playground/blob/main/golden_angle_sample/Sample%20XD-GRASP%20Type%20Radial%20-%20Single%20Coil.ipynb)**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CARDIAL-nyu/cmr-playground/blob/main/golden_angle_sample/Sample%20XD-GRASP%20Type%20Radial%20-%20Single%20Coil.ipynb)
 - **2. [Multi-Coil/Multi-Frame Demo](https://github.com/CARDIAL-nyu/cmr-playground/blob/main/golden_angle_sample/Sample%20XD-GRASP%20Type%20Radial%20-%20Multi%20Coil.ipynb)**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CARDIAL-nyu/cmr-playground/blob/main/golden_angle_sample/Sample%20XD-GRASP%20Type%20Radial%20-%20Multi%20Coil.ipynb)
 - **3. Cartesian OCMR to GRASP OCMR**: *TODO*
 - **4. [Baseline Compressed Sensing Reconstruction](https://colab.research.google.com/drive/1sGbdbfBHlELVylowWTzMoBVU2JsSPjJd?usp=sharing)**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1sGbdbfBHlELVylowWTzMoBVU2JsSPjJd?usp=sharing)

## Quickstart

 - Create a conda environment with the necessary dependencies to run the Jupyter notebook

```bash
  conda create -n cmr_playground python=3.7 numpy scipy matplotlib jupyter ipykernel ipympl sigpy seaborn -c conda-forge -c frankong
  conda activate cmr_playground
  python -m ipykernel install --user --name cmr_playground --display-name "Python 3.7 (cmr_playground)"
```
