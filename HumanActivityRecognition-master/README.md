# HumanActivityRecognition

# objective

To classify common human activities like walking,standing,laying on the basis of readings obtained from smartphone sensors

# Dataset

Source: UCI ML Repository

Human Activity Recognition Using Smartphones Data Set

https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones#

# Model

Dataset has 561 attributes so Principal Component Analysis(PCA) is used to reduce the dimension.

Best results are obtained by taking about 220 principal components.

Linear SVM("one vs one") was used to classify the data

# About Repository

ActivityRecognition.py --- code(implemented on google colab)

HAR_PCA.png -- image showing 2 principal components of the data(Data Visualization using 2 attributes)

HAR_VAR.png -- shows a plot of variance vs the number of attributes in the train data

# Results

Training accuracy ~ 99.5%

Development or cross-validation accuracy ~ 98%

Testing accuracy ~ 95-96%

Most mis-classifications were obtained for standing and sitting classes as there is not quite of a difference between the 2 postures.

# Future Scope

Neural networks(with some optimizations) can be tried for the dataset
