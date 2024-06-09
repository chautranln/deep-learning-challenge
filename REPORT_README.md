# Report
Overview of the Analysis:
The purpose of this analysis is use TensorFlow, to predict whether ventures funded by Alaphbet Soup will be successful. The dataset contains over 34,000 organizations and their information (including identification, application type, affiliation, classification, use case, org type, status, special considerations, funding amount requested, and effective financial use). 

Data Preprocessing:
What variable(s) are the target(s) for your model? The target variable for the model is the "IS_SUCCESSFUL" data, which indicates whether the funding was used effectively.
    
What variable(s) are the features for your model? The features for the original model include all columns except "IS_SUCCESSFUL", "EIN", and "NAME."

What variable(s) should be removed from the input data because they are neither targets nor features? "EIN" and "NAME"

Compiling, Training, and Evaluating the Model:
How many neurons, layers, and activation functions did you select for your neural network model, and why? The original neural network model had three hidden layers. The first consisted of 80 neurons, second had 30 meaurons, and the output had 1 neuron. ReLU activation functions are used for the hidden layer and a sigmoid activation function was used for the output layer. 

Were you able to achieve the target model performance? The target model performance was an accuracy of over 75%. However, my model achieved an accuracy of 72%.

What steps did you take in your attempts to increase model performance?
I made three attempts to increase model performance. I dropped more columns (STATUS, SPECIAL_CONSIDERATIONS, ASK_AMT),added more layers, and adjusted the number of neurons. 

Summary: 
I made multiple attempts to optimize the model, but unfortunately, the achieved accuracy fell short of the desired 75% accuracy by approximately 3% across all three attempts. To improve classification accuracy, a different model structure that can handle nuumerical and categorical features effectively should be applied. Additionally, feature engineering and hyperparameter experimentation could be attempted to enhance the performance. 

# deep-learning-challenge
For this challenge, I utilized previous class examples to complete the analysis. Additionally, I used chatgbt to troubleshoot errors and provide direction for whenever I got stuck on an issue. 
