# Heart-Failure-Detection
Heart failure is a serious problem which has a huge impact on people’s life. With the accelerated pace
of life, increased portion sizes and inactivity, most people always ignore their health. Moreover,
because of the environmental deterioration, those factors can lead to the issue of heart failure which
can become more and more common in the future. If people did not pay attention to the issue of heart
failure, it would finally cause the death.
In the past years, different researchers used different methods to collect and analyze data with the
aim to predict heart failure. These data include electronic health record (EHR) data of patients with
heart failure in different hospitals from different countries, Cleveland heart disease dataset, biomedical
science datasets from UCI, etc. Based on these data, various methods are being applied, e.g.,
predicting the survival of patients by utilizing classifiers of machine learning, using supervised deep
learning and machine learning algorithms, training a boosted decision tree algorithm, utilizing
machine intelligence-based statistical model, random under-sampling method and deep neural network
models, using bioinformatic explainable deep neural network (BioExpDNN), etc.
Although there are some work based on machine learning, comprehensive comparisons between
different models have not been made, nor have new models such as Deep Forest been attempted. The
work of this paper can fill these inadequacies. We use F1 score and accuracy as the evaluation metrics.
The F1 score reflects the robustness of the model, and the accuracy reflects the overall accuracy. First,
with the min-max normalization method, the results of 18 models are compared. It can be seen from
the accuracy that SMOTE (Synthetic Minority Over-pling Technique) method is higher than that
without SMOTE method, and it can be seen from the comparison of F1 score that SMOTE method is
higher than that without SMOTE method. By comparing the z-score normalization methods with the
18 models, the accuracy of the SMOTE method is higher than that of the non-SMOTE method, and
the F1 score comparison shows that the SMOTE method is higher than that of the non-SMOTE
method. Overall, the z-score normalization method is better than the min-max normalization method.
