# What is explainable Ai?
Explainable AI also be referred to as interpretable Machine Learning, provide techniques to better understand and validate how a model works or how the outp is acquired. 
Understanding the model and its behaviour is not only relevant for the devolopers but also the end users who uses them.
For example, the out of tech industries like health care needs a better understanding in the models that are going to be used in their workspace.

The complexity of the models are being increased day by day, which reduces the interpretability. 
The basic models are a lot interpretable but less acuurate. Whereas, the complex models like neural networls and Deep Learning models are more complicated and more accurate but least interpretabale. 
As we refer them to as blackbox algorithms, to better understand those explainable AI comes into the picture.

# What is SHAP?
SHapely Additive exPlanations(SHAP) is a framework used to interpret Machine Learning models. Unlike other methods, SHAP helps in identifying and understanding the individual feature predictions. 
The idea behind SHAP is based on the cooperative game theory. In cooperative game theory, the Shapley value is a method for fairly distributing the total gains or costs among a group of players who have collaborated.

SHAP is a model-agnostic, which means it can be applied to any type model to interpret. 

# What is SHAP Value?
Shap value measures the impact of feature on the target variable, basically the contribution of individual feature towards the prediction.

Positive shap value indicates that a feature positively impacts the prediction. It is directly proportional to the target variable.

Negative shap vlaues indicate that there is a negative influence on the target variable. Inversely proportional.
