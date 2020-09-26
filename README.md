# ESP32CAMToS3
Arduino and AWS Lambda Code for pushing images to AWS S3

To use this code, change the Arduino file witn your own AWS S3 Address.

String post_url2 = "https://awswebaddress/prod/" + MAC + "/" + Time; // Location where images are POSTED


Change the Wifi username and password

const char* ssid = "*****";

const char* password = "*****";


These are the files in this repository.

S3LambdaCode.js

The lambda code that goes into the Lambda function that API uses to get the file to S3.


UploadToS3.ino

The upload program that will get uploaded onto the ESP32


UploadToS3_DeepSleepVersion.ino

A deepsleep version of UploadToS3 which is identical apart from using deep sleep instead of a simple timer and also uses more robust wifi code .
