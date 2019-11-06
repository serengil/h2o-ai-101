# h2o-ai-101

This repository includes h2o.ai based machine learning project implementations and documentations.

1- **h2o frame** [`Tutorial`](https://sefiks.com/2019/09/13/h2o-frame-calling-forth-the-power-of-ten-tigers/)

Pandas is de facto standard for data manipulation operations among data scientist. It is fast but it runs on single cpu core. Herein, h2o frame is a powerful alternative to pandas. It supports multi-core calculations whereas it covers almost same functions with Pandas.

2- **h2o GBM** [`Code`](https://github.com/serengil/h2o-ai-101/blob/master/python/H2O-GBM.ipynb), [`Tutorial`](https://sefiks.com/2019/09/18/a-gentle-introduction-to-h2o-gbm/)

GBM dominates tabular data based kaggle competitions nowadays. Herein, h2o covers both XGBoost and its own GBM. This is a gentle introduction to h2o GBM.

3- **h2o AutoML** [`Code`](https://github.com/serengil/h2o-ai-101/blob/master/python/H2O-AutoML.ipynb), [`Tutorial`](https://sefiks.com/2019/09/03/a-gentle-introduction-to-h2o-automl/)

The hottest topic in machine learning is AutoML. Even though model design is accepted as state-of-the-art, today AutoML can design better models than us. h2o AutoML covers linear models, tree-based models including random forest and gradient boosting (XGBoost and h2o GBM) and deep learning (regular fully connected neural networks).

4- **Explaining h2o models with Lime** [`Code`](https://github.com/serengil/h2o-ai-101/blob/master/python/h2o-lime.ipynb), [`Tutorial`](https://sefiks.com/2019/09/19/explaining-h2o-models-with-lime/)

Interpretability and accuracy are inversely proportional concepts. You cannot deploy unexplainable models to production even if they have high accuracy. Here, lime offers to explain custom predictions of your built models.

5- **Interpratable Machine Learning with H2O and SHAP** [`Code`](https://github.com/serengil/h2o-ai-101/blob/master/python/h2o-shap.ipynb), [`Tutorial`](https://sefiks.com/2019/10/10/interpretable-machine-learning-with-h2o-and-shap/)

SHAP offers very deeply explanations for built models against LIME. Still, it comes with a time cost. You should use SHAP if you have enough time to analysis your model.

# Requirements

I have tested this repository on the following environment configurations. Confirm your environment is same as below to avoid environmental issues.

```
>>> !python --version
Python 3.6.3
>>> import h2o
>>> h2o.__version__
3.26.0.3
```

# Support

There are many ways to support a project - starring the GitHub repos is one.

# Licence

This repository is licensed under MIT license - see [`LICENSE`](https://github.com/serengil/h2o-ai-101/blob/master/LICENSE) for more details
