# Advertisement-Success-Prediction : Overview
* Predicting the 'netgain'(0/1) outcome of an advertisement campaign.
* Features include target-audiance, industry and demographic  details.
* Imbalanced dataset.
* Evaluation Matrix : F1_score 


##### This will help guide decision-making for the firm, as they will want to pursue ads that are likely to generate a net gain for their clients— thereby boosting the advertising firm’s reputation.
#### Model Building :
* After EDA and cleaning, Encoding was done to the categorical features.
* OneHotEncoding for nominal variables using get_dummies methods.
* OrdinalEncoding for ordinal variables using OrdinalEncoder from sklearn.
* As the data is imbalanced, different sampling methods were tried out.
* Oversampling using SMOTE or Synthetic Minority Oversampling Technique.
* Undersampling using RandomUnderSampler.
*  Models fitted and evaluated :
*  1. LogisticRegression
*  2. RandomForestClassifier
*  3. XGBClassifier
*  4. AdaboostClassifier
*  5. VotingClassifier
