# Running the Notebook in VSCode and Colab

The Colab notebook should run smoothly in VSCode with minimal or no modifications, as long as you have the necessary dependencies installed.

## Checklist for Running in VSCode:

1. **Install Required Libraries:**  
   Make sure you have the same Python packages installed in your VSCode environment.  
   Run this in your terminal or Anaconda prompt:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn

2. Check for File Paths:
If your notebook uses any local file paths (e.g., data/housing_California.csv), ensure the files are accessible in the same directory structure when running in VSCode.

3. Kernel Selection in VSCode:
Make sure you're using the correct Python environment with all the required libraries.

1. Matplotlib Backend Settings:
If you encounter issues with plotting, add the following to the top of your notebook:
`%matplotlib inline`
This ensures the plots display correctly in the notebook interface within VSCode.

1. Cell Execution:
In VSCode, just like in Colab, you can run cells individually by pressing `Shift + Enter`. You can also run all cells by selecting Run All from the notebook toolbar.

1. Random State Reproducibility:
Since we are using `random_state=42` throughout our code, you can expect identical results between Colab and VSCode runs.
