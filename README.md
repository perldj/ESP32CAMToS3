# ESP32CAMToS3
Arduino and AWS Lambda Code for pushing images to AWS S3

To use this code, change the Arduino file witn your own AWS S3 Address.

String post_url2 = "https://awswebaddress/prod/" + MAC + "/" + Time; // Location where images are POSTED


Change the Wifi username and password

const char* ssid = "*****";

const char* password = "*****";
