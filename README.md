## ADO pipeline to run the terratest code to test the subscription module.

### This template will help us to run the terratest code to test the subscription module using golang. TO run this templete you must have the terraform module of subcription. You can pass the path of that folder in the main_test.go and then run the terratest code.
----------
## You can follow the below step to run the terratest:

### Step1:- setup the credential in the library section and call that library in the pipeline. For example, I have define my library name as Azure_credential and i am calling with this name.


### Step2:- Trigger the ADO pipeline manually because i have mention it to runn manually.