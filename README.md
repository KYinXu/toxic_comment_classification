# Exploring Transformers and Ensembling Techniques in Text Classification

Full breakdown: https://acrobat.adobe.com/id/urn:aaid:sc:US:d0c07644-479f-4f41-adf4-5e414105c21a

The purpose of this project is to explore cheap alternatives to modern NLP techniques to yield similar results. Transformers are the current leading approach for learning text-based datasets, but their main tradeoff is complexity and immense computational cost. Using the Kaggle Toxic Comment dataset, we attempt to replace the standard feed-forward neural network for classification with a simpler linear regression model. We dive into simple base models in `cnn_naivebayes.ipynb`, `logistic_regression.ipynb`, and `transformer.ipynb` for comparison purposes. The final experimental model can be found in `ensemble_approach`, and figures on dataset analysis can be found in `data_visualization.ipynb`.
```
├── data/
│   ├── train.csv
│   ├── test.csv
│   └── test_labels.csv
├── cnn_naivebayes.ipynb
├── data_visualization.ipynb
├── ensemble_approach.ipynb
├── logistic_regression.ipynb
├── transformer.ipynb
├── README.md
└── .gitignore
```