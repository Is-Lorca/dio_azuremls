> # Bike rental predictions using Azure Machine Learning
>> ## Step by Step:
>> 1. Create a workspace: making able to use Azure Machine Learning studio to work with the resources we will need
>> --------------------------------------
>> 2. Create a new Automated ML job with the recommended settings.
>> 3. Submit the training job, it starts automatically.
>> 4. After the job finish, review the best model, selecting the text under the Algorithm name, then --> Metrics and select the residuals and predicted_true charts if they are not already selected.
>> --------------------------------------
>> 5. On the Model tab, select Deploy and use the Web service option to deploy the model with the recommended settings.
>> --------------------------------------
>> 6. Test the deploy service using the Endpoints, located in the left hand menu, then open the predict-rentals real-time endpoint.
>> 7. On the predict-rentals real-time endpoint page view the Test tab and, in the Input data to test endpoint, replace the template JSON with the right input data.
>> 8. Click the Test button and review the test results, which include the predicted number of rentals based on the input features, if the code is right.
>> ---------------------------------------
>> 9. Delete the endpoint to avoid accruing unnecessary Azure usage, after finishing all the experiments.
