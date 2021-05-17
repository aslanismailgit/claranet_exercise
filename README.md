# SQL Analytics Problem
-	I worked on Data Analytics and Model Development.
-	I used jupyter notebook for this study, my preferred IDE is vscode.
-	I see the problem as an NLP problem. SQL queries make up the vocabulary/dictionary and query time is a continuous target. So, this can be treated as an NLP Regression problem.

# Some Highlights 
-	Some hours are more loaded than others, so database manager should consider/investigate for causes/remedies
-	Wordcloud plots provide insight about sql queries in different periods.
-	As a performance metric, I used r2, MAE and RMSE.
-	Since r2 gives opportunity to compare different models, it will be more important to track r2.
-	I also draw some plots to evaluate model’s prediction performance. Eye-ball is always good to have at some degree.
-	I developed ML/DL models using sckit-learn, tensorflow, keras and huggingface libraries. Some of them are just for demonstration purposes.
-	I used train/validation and test split to develop models. I tweaked the parameters using train/validation sets a little bit, but not pushed too much.
-	I tried an ensemble of different models.
-	I used CV, GridSearch, and RandomSearch for parameter tuning
-	At the final step, I created a sklearn pipeline to develop a model that can make predictions using row query text.
-	To compare the different models, I also measured model size on disk and prediction times. Those make a difference on the deployment phase.
-	To get reasonable results, I applied standardization to target during DL model training. (the standardization parameters are taken from train set)
-	I think it is always good to choose a light weight model if performances are the same. For example, xgboost algorithm is easy to train and light-weighted compared to keras models.
-	Big does not mean better as seen in BERT model.
