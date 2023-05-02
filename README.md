# Implementing a simple serverless application which uses Web Identity Federation.  
![image](https://user-images.githubusercontent.com/73319030/235738466-1447b8fa-96dc-4b82-b4f1-b9d9651af324.png)

## The application runs using the following technologies

- S3 for front-end application hosting

- Google API Project as an ID Provider

- Cognito and IAM Roles to swap Google Token for AWS credentials

The application runs from a browser, gets the user to login using a Google ID and then loads all images from a private S3 bucket into a browser using presignedURLs.  

This advanced demo consists of 6 stages :-  

- STAGE 1 : Provision the environment and review tasks    

- STAGE 2 : Create Google API Project & Client ID  

- STAGE 3 : Create Cognito Identity Pool  

- STAGE 4 : Update App Bucket & Test Application
