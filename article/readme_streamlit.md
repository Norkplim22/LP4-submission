# A SALES PREDICTOR WEB APP WITH AN EMBEDDED MACHINE LEARNING MODEL USING STREAMLIT

Introduction
Sales is crucial in every retail industry. Usually, management decisions are made based on sales forecast hence, understanding the patterns and trends of the purchasing behaviours of customers are crucial to optimize inventory, product placement, and marketing strategies. Thereby accurately predicting sales allows retailers to make informed decisions that drive revenue growth.

Unlike in the days of old where there was difficulty in sales prediction, technological advancement has made it easier. With the help of Machine Learning (ML) and Artificial Intelligence tools, industries can leverage large amount of data with diversified information to accurately predict sales.

Project summary
In this project, an interactive webapp was designed using streamlit. Furthermore, an ML model trained for predicting sales in a previous project was embedded to enable retailers input information on the front end and get sales prediction. The major tools used here was streamlit and Python.

Building the ML model
Here is a flowchart summarising the processes used to train and export the ML model and its components for the current project.


ML model process
Webapp
The webapp was designed using streamlit. Streamlit is an open-source Python framework that allows for easy design of web applications and data visualizations. It is simple and easy to use and provides an interactive and responsive user interface. It focuses mainly on data science and machine learning applications hence requiring little to no knowledge of web development languages such as HTML, CSS, or JavaScript. Furthermore, streamlit is very reactive in that changes in the user interface automatically trigger updates to the application’s output. Because of its focus on data science, most data science libraries are supported.

For this project, the webapp was designed in a virtual environment. After creating and activating the virtual environment, the requirements were installed and the app interface created.

App Interface


Frontend app visuals
To design the app, all necessary libraries were imported. These include pandas, numpy, scikit-learn, and Streamlit. The best model saved from the previous project was also loaded together with its component. The loaded model will be used for predictions of data entered on the frontend.

After loading all necessary components, the input columns of the webapp were created using streamlit functions. Streamlit widgets like st.number_input, st.slider, and st.selectbox were used. The various inputs required for the model were defined with the various specifications to enable users to enter the right information on the app.

The working idea is that once the user enters the details on the interface, the variable entered will be converted into a pandas dataframe and taken through the various pre-processing steps used to train the model and then the loaded model will predict on the processed dataframe from the interface.

To achieve this, a function was created to help transform the variable from the users' interface into a dataframe and the dataframe subjected to pre-processing.


Codes for pre-processing and prediction
After pre-processing, the processed data was used to predict sales using the pre-trained model loaded and the results converted into a csv file.


sample prediction
The details of the project and codes can be found on Github.

https://github.com/Norkplim22/Apps.git 
