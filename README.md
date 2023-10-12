# Loan-Eligibility-application-machine-learning-model-using-streamlit
Model Loading: In the code, the trained machine learning model is loaded from a saved pickle file using the pickle.load() method. This model is used to make loan eligibility predictions based on user input.

User Input: The application allows the user to enter information such as Gender, Marital Status, Monthly Income in Rupees (ApplicantIncome), and Loan Amount in Rupees (LoanAmount). Users can make selections and input data via Streamlit widgets like select boxes and number input fields.

Prediction: When the user clicks the "Check" button, the prediction function is called. This function processes the user's input data and passes it to the loaded machine learning model. The model then predicts whether the loan application is "Approved" or "Rejected." The result of this prediction is displayed to the user.

Streamlit Interface: The Streamlit interface is defined in the main function. It creates a simple web page with a yellow header and a title, and it uses Streamlit's st.markdown and st.button functions to present the user interface. The final loan eligibility status is displayed using st.success.

This code demonstrates a basic example of how to create a user-friendly interface for a machine learning model using Streamlit. It's essential to ensure that the trained model and the application's dependencies are set up correctly before running the code.
![loan Eligibility applicaton](https://github.com/PrajaktaPatil1/Loan-Eligibility-application-machine-learning-model-using-streamlit/blob/main/Screenshot%20(398).png)
