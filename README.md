# Dimensionality Reduction & Regression Analysis

This project demonstrates the use of matrix factorization techniques (PCA and SVD) for data compression and predictive modeling. 

## Key Features
* **Dimensionality Reduction:** Compressed a 150-feature dataset into 10 Principal Components while monitoring variance retention.
* **Automated EDA:** Utilized `AutoViz` for rapid visualization of feature distributions.
* **Regression Suite:** Implemented and compared Linear, Ridge, and Lasso regression models to evaluate predictive accuracy using MSE and RMSE.
* **Image Compression:** Applied Singular Value Decomposition (SVD) to reduce image file size while maintaining visual integrity at various rank (r) approximations.

## Tech Stack
* **Language:** Python
* **Libraries:** Scikit-Learn, NumPy, Pandas, Matplotlib, Seaborn, AutoViz
* **Environment:** Google Colab

## Results
The notebook contains pre-rendered visualizations showing the image reconstruction at $r=30, 50, 75$ and the cumulative variance plots for the PCA analysis.
