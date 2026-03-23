# End-To-End-Data-Science-Project

Company Name : CodeTech IT solutions

Name: Akashy Deepak

Domain : Data Science

Intern ID : CTIS6565

Duration : 4 weeks

mentor : Neela Santosh

descprition of the task :

This project demonstrates the development of a simple machine learning web application using Flask for predicting salaries based on years of experience. It integrates model training and deployment, showcasing how machine learning models can be used in real-world applications.

The project consists of two main parts: model creation and web application deployment. In the first part, a dataset named salary.csv is loaded using the Pandas library. This dataset contains two columns: experience (independent variable) and salary (dependent variable). The data is then separated into input features (X) and target output (y), where experience is used to predict salary.

A Linear Regression model from Scikit-learn is used to train the data. Linear Regression is a simple and widely used algorithm for predicting continuous values. The model learns the relationship between experience and salary by fitting a straight line to the data. Once trained, the model is saved using the Pickle library as a file named model.pkl. This step is important because it allows the trained model to be reused later without retraining.

In the second part, a web application is created using the Flask framework. Flask is a lightweight web framework in Python that allows easy integration of machine learning models into web interfaces. The saved model (model.pkl) is loaded into the Flask application using Pickle.

The application defines two routes. The first route ("/") serves as the home page and displays a simple HTML form. This form allows the user to input their years of experience. When the user submits the form, the data is sent to the second route ("/predict") using the POST method.

In the "/predict" route, the input value entered by the user is retrieved using request.form. The value is converted into a float and passed to the trained model for prediction. The model then calculates the predicted salary based on the given experience. The result is displayed back to the user in a simple text format.

The application is run using app.run(debug=True), which enables debugging and automatically reloads the server when changes are made to the code. This is useful during development.

One important aspect to consider is the file path used for loading the model. Proper path formatting (using raw strings or forward slashes) ensures that the file is correctly located and loaded without errors.

Overall, this project illustrates the complete workflow of a machine learning application—from data loading and model training to deployment using a web interface. It highlights how simple models can be integrated into user-friendly applications, making predictions accessible to non-technical users.

This project serves as a strong foundation for more advanced applications, such as adding multiple input features, improving the user interface, or deploying the app online using cloud platforms.

output of the task :

<img width="625" height="46" alt="Image" src="https://github.com/user-attachments/assets/e20d8edc-3755-4fda-8ec8-de2ef2b346a3" />
<img width="747" height="141" alt="Image" src="https://github.com/user-attachments/assets/f3497f29-3143-48a4-90df-3ee16ed22344" />
<img width="518" height="154" alt="Image" src="https://github.com/user-attachments/assets/c6921909-0730-44e1-bc4a-0087f85a4405" />
<img width="448" height="70" alt="Image" src="https://github.com/user-attachments/assets/2cc49da0-feef-4d2e-bc71-810b0c1bcfb9" />
