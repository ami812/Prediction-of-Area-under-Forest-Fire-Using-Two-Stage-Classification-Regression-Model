# Prediction-of-Area-under-Forest-Fire-Using-Two-Stage-Classification-Regression-Model
Forest fires are a significant environmental hazard, causing widespread damage to ecosystems, wildlife, human 
life, and property. They contribute to severe environmental degradation, including deforestation, biodiversity 
loss, and air pollution. Accurate prediction of forest fires is essential for safeguarding human lives, minimizing 
economic losses, protecting ecosystems, and ensuring the efficient allocation of firefighting resources. In the 
context of rising global temperatures and more frequent wildfires, the need for precise fire prediction is more 
urgent than ever. In this project, we explored various regression and classification techniques to predict the 
extent of forest fires in Montesinho Natural Park. Our best-performing model is a two-stage approach 
combining a Random Forest Classifier and a Random Forest Regressor. The classifier first predicts whether 
the area burnt under forest fire is 0 hectares or more (binary output). If the burnt area of 0 hectares is predicted, 
the regression model outputs zero for the burned area. If a burnt area of more than 0 hectares is predicted, the 
regression model estimates the area affected. The final model achieved a Root Mean Squared Error (RMSE)
of 2.5436 hectares, R² of 0.648, and an adjusted R² of 0.629. This model can be further refined by incorporating 
additional physical factors and constraints for improved accuracy.
