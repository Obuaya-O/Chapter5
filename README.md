# Chapter4
Our EUCT-NS dataset is composed of 190 rows of data with 4 numerical input variables and a target variable (endpoint type) with three class values; patient final outcome, intermediate endpoint and surrogate outcome (multiclass classification).

Our NS-HRA dataset is composed of 694 rows of data with 3 numerical input variables and the same  target variable as above with the same three class values

These datasets were formed to determine if machine learning could be used to classify when a surrogate outcome was used as the primary endpoint in a nervous system clinical trial. This knowledge would then be used to evaluate surrogate outcome use (thesis implication) and improve the transparency of reporting when a surrogate outcome is used (wider implication).

The MLP classifier was trained on the EUCT-NS dataset with a 80/20 split. The MLP model was then applied to the NS-HRA dataset and the predicted labels were generated.
