# vivli_bp_model

### Contains the pkl file of the the model described in our associated publication. 

#### This model was created using our vulcan framework and the hyperparameters listed in the paper. 

#### The data scaler is a sklearn object https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html for which the variable ordering is     

```
var_ordering_scaling = [
    "bsi6","qlesq7","Race","madrs3","ad_demog_tak_01","madrs7","hamd6","hamd16","qlesq3","qids14","ymrs_07","ymrs_04","scl64","qids15","qlesq14","scl64","qids13","scl32","hama13","madrs9","qlesq13","qids5","hama10","sds2","cgi1","madrs6","qids2","qids16","hama4","ymrs_05","qids11","madrs1","qids12","madrs8","treatment"
]
```

#### The equating object is a python dictionary that contains the equipercentile transformations needed as described in the associated publication.