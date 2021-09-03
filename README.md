# Hockey Position Classification   
Using demographic & scoring statistics, can I accurately classify players within the following 4 positions? Center, Defense-men, Right Wing, Left Wing.  
For an overview, please click [here](https://github.com/janniec/Hockey_Positions_Classifier/blob/master/PredictingHockeyPositions.pdf "Presentation").
  
## Tools
  * SQL  
  * PostgreSQL  
  * SKLearn  
  * ROC Curve  
  * GridSearch CV  
  * Logistic Regression  
  * Gaussian Naive Bayes  
  * Random Forest Classifier  
  * Confusion Matrix  
  * D3.js  
    
## Data  
Data was acquired from the Professional Hockey Database on  [Kaggle](https://www.kaggle.com/open-source-sports/professional-hockey-database "Professional Hockey Database"), specifically:  
* Master.csv: This dataset contains biographical statistics on each hockey player.  
* Scoring.csv: This dataset contains scoring statistics on each hockey player.    

## Models  
Data was stored in SQL tables on AWS, Amazon Web Service. Using SQL Alchemy, I cleaned my data through Jupyter Notebook before creating classification models. See [Predicting_Hockey_Positions.ipynb](https://github.com/janniec/Hockey_Positions_Classifier/blob/master/Predicting_Hockey_Positions.ipynb).   

## D3 Visualizations  
Visualization of the confusion matrices for all the models were created using D3. Main D3 programming was done in [confusion_matrix.html](https://github.com/janniec/Hockey_Positions_Classifier/blob/master/D3_viz/confusion_matrix.html), supported by css stylesheet ([style.css](https://github.com/janniec/Hockey_Positions_Classifier/blob/master/D3_viz/style.css)) and javascript file ([main.js](https://github.com/janniec/Hockey_Positions_Classifier/blob/master/D3_viz/main.js)).  Confusion_matrix.html can be run in your local browser for your viewing pleasure.
