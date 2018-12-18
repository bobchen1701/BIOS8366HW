# Project Evaluation:

- introduction of problem, description of methods, discussion of results: 16/20
- data preparation 8/10
- implementation of methods: 17/20
- runnable by third party: 10/10
- cross-validation and model selection: 7/10
- visualization: 8/10
- model checking: 7/10
- evaluation of performance characteristics: 7/10

## Comments: 

I was disappointed to see you flying solo, as this was supposed to be a group project. Nevertheless, not a bad effort. More thought needed to be applied to the data processing, especially with respect to individuals with multiple admissions. Also, there are a few exclusion criteria that should have been applied to the dataset (or otherwise justified) -- e.g. what to do about outpatients, kids, psych patients, etc. Cleaning methods could have been more idiomatic as well.

On the modeling side, some model/variable selection is needed for the regression modeling. In general, for classification metrics, accuracy is not a useful criterion when class imbalance exists. If you predict all outcomes to be non-readmissions with this dataset, you will get 70-80% accuracy, depending on your analysis dataset. Better to use something that emphasizes getting the true positives (recall/PPV/ROC-AUC).

SCORE: 80/100