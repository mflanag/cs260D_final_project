# cs260d_project.ipynb
This Jupyter notebook is the primary code used to run the experiments presented in the paper.

To run open the notebook in either a Google Colab session or in a Jupyter notebook that can support the following packages.
  - Python3
  - pytorch
  - numpy
  - matplotlib
  - pandas

From inside the notebook ensure that the constants CLEAR_CACHE and LOAD are both set to False. Then run all cells in sequential order. This should produce the same results as seen in the paper.

The models and selected subsets get saved to the same directory level under the models folder. For quicker re-runs once the models are present set the LOAD constant to True.

# advanced_poisoning.ipynb
This Jupyter notebook focuses on the future work described in the conclusion. It investigates using ResNet50 instead of 18, applying different poison rates, and using different poisoning techniques.

To run open the notebook in either a Google Colab session or in a Jupyter notebook that can support the following packages.
  - Python3
  - tensorflow
  - sklearn
  - numpy
  - cleverhans
  - A google drive authorization for model saving

Running this notebook just requires running the cells in sequential order.
