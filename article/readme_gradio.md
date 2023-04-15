# CUSTOMER ATTRITION PREDICTION WEB APP DESIGNED WITH GRADIO.

Introduction
Customer churn is used to describe the percentage of customers that stop using a company’s product or service within a specific period. It is a common phenomenon across all industries, as it can result in significant loss of revenue and bankruptcy.

In highly competitive markets, customer attrition is a major crisis and so customer retention is a topmost priority due to the high cost involved in acquiring new customers than maintaining old ones. Identifying customers at the risk of churning and developing strategies to retain them is crucial. With enormous available data and technological advancements, predicting customers at the risk of churning has become easier. Therefore, companies need to identify customers who are likely to churn and take proactive measures to retain them by improving incentives, marketing strategies and customer service.

In a previous project, a model was developed to predict customer churn/attrition rate. In this project, I explored how to integrate the developed model with Gradio to build an interactive customer churn prediction web app. The app will equip businesses with the ability to predict risk customers and take proactive measures to retain them.

Training the model
Below is a summary of the processes used to train the model.


Training the model

Exporting the model
Webapp
Gradio is an open-source Python library that allows for the creation of custom web interfaces for machine learning models. Having an interactive interface helps to transform complex machine learning models into simple web apps that anyone can use even without programming knowledge. Gradio is compatible with a wide range of input and output types: text, images, audio, and video. Furthermore, Gradio also supports a wide range of machine learning frameworks, including TensorFlow, PyTorch, Scikit-learn, and Keras hence easily compatible with all machine learning framework.

For this project, the webapp was designed in a virtual environment. After creating and activating the virtual environment, the requirements were installed, and the app interface created.

App design and Interface

Frontend app visuals
To design the app, all necessary libraries (Gradio, pickle, pandas, numpy, joblib, and PIL) were imported. The best model saved from the previous project was also loaded together with its component. The loaded model was used for the prediction of data entered on the frontend.


Loading ML model
After loading all necessary components, the input columns of the webapp were created using Gradio functions. The variables to be entered from the users’ interface will be converted into a dataframe and the dataframe subjected to pre-processing. A function was created to process and predict the data entered on the frontend.


The webapp interface was then created by defining with the inputs required and their specifications to enable users to enter the right information on the app.


Creating the Gradio interface
The working idea is that once the user enters the details on the interface, the variable entered will be converted into a pandas dataframe and taken through the various pre-processing steps used to train the model and then the loaded model will predict on the processed dataframe from the interface.

Find attached a sample prediction conducted.




In conclusion, the app will be helpful to businesses by leveraging historical trends and patterns of business data and machine learning tools to alleviate a major challenge and promote business growth.

Please host the drafts and all the materials, including the final version, related to your article in this folder.
