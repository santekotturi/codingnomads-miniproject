# CodingNomads Deep Learning Project 1: Fundamentals

The purpose of this project is to practice some of the skills you've learned in the **Fundamentals** module, including loading data and training and evaluating an ML model using `torch`.
Although deep learning should not be your first approach when working with tabular data, it's a natural transition from the DS/ML course.

Why shouldn't DL be your first approach? [This paper](https://arxiv.org/pdf/2110.01889.pdf) compares many methods on the `adult` dataset, a cannonical tabular dataset.
The figure below from the paper compares many methods on tabular data, and frameworks like [XGBoost](https://xgboost.readthedocs.io/en/stable/), [catboost](https://catboost.ai/), and even `sklearn`'s Random Forest demonstrate great results.

<a>
    <img
         class="img-responsive" 
         src="https://github.com/CodingNomads/static/blob/main/DSML/deep_learning/snapshots/xgboost_dl_tabular.png?raw=true"
     />
</a>

\- [Deep Neural Networks and Tabular Data: A Survey](https://arxiv.org/pdf/2110.01889.pdf)

Kaggle Grandmaster Bojan Tunguz has some great advice on how to approach tabular data problems:

> My first “serious” steps in a competition involve some light EDA and building a simple first model or two, usually just a simple XGBoost, LightGBM, or both.

\- [Interview with Kaggle GrandMaster, Data Scientist: Dr. Bojan Tunguz](https://medium.com/dsnet/interview-with-kaggle-grandmaster-dr-bojan-tunguz-726b28e601e)

In the spirit of this advice, you will load and split your data, do some EDA, train a non-deep learning model, and train a deep learning model.
Finally, you will write a report describing your model selection process and performance on your test dataset.