### Practical Machine Learning
This is a submission for the John Hopkins Practical Machine Learning Course.

The report covers:
- **Data preparation**: loading, cleaning (removing NA columns and non-predictive features), and partitioning the WLE dataset
- **Model building**: Random Forest, Gradient Boosting (GBM), and Linear Discriminant Analysis (LDA)
- **Model comparison**: resampling-based accuracy comparison across all three models
- **Model selection**: Random Forest chosen and re-trained with 5-fold cross-validation (`ntree=250`)
- **Validation**: confusion matrix and accuracy/kappa on the held-out validation set
- **Out-of-sample error**: computed as `1 - accuracy` on the validation set
- **Variable importance**: top-20 most important predictors visualised
- **Test set predictions**: quiz predictions generated from the final model

Peer reviewer, please open the <a href="report.md">Report file here.</a>
