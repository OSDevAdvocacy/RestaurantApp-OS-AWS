# AWSBengalore
Content of the exercise done in the AWS User Group in Bengalore

This repository contains the main components for you to implement a Restaurant App with OutSystems.

This application shows a list of Restaurants in Bengalore. You can see the details of the restaurant and you can take a picture that it's analysed by Rekognition and is submitted to S3.

Here are the pre-requisites :

AWS
1 - You'll need one bucket on S3 with the name os-restaurant-images
2 - You'll need one DynamoDB Table with the name Restaurant populated with the data from the JSON in the Data folder
3 - You'll need access to Rekognition
4 - You'll need an IAM user configured with access to these 3 services 
5 - You'll need to make sure that the S3 and the DynamoDB table are set in the same region

AWS CLI
1 - You'll need to have the AWS CLI installed on your machine

OutSystems
1 - You'll need to have the following components installed on your environment:
- DynamoDB connector 
- Amazon Simple storage Service
- Camera Plugin
- Common Plugin
2 - Install the starter app and the Customized version of the Amazon Rekognition
3 - Confirue the Site Properties of the Starter app
4 - Open the code of the starter app and on the GetMapsKey action put a Google Maps Key with the Maps Static API active