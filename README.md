# DAMG7245-Assignment4: CITIBIKE MACHINE LEARNING HANDS-ON-LAB WITH SNOWPARK PYTHON

Codelabs document link -> https://codelabs-preview.appspot.com/?file_id=1Zh7N2oGdKIB8jsKvXg9uHMSizSLyIOOpkhSkZRDoExY#2 

1. Data Engineering: 

	- In this step code is exported to functional modules so that the MLOps team can use it

	- We have also implemented an incremental ELT for every month reload as well as for bulk load

2. Data Science:

	- Built a Machine Learning Model using Regression, taking the top most station ID 

	- split the data for last 365 days for valid or test 

	- added holidays table as features then weather data as features

	- Trained and predicted the model accuracy 

3. ML Engineering:

	- automate the inputs from Data Engineering and Data Science by creating functions

4. ML OPs:

	- Created a setup task flow with bulk edit and initial schemas 

	- Created monthly task flow with incremental ingest  
