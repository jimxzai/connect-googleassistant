# How to connect to google assistant for NLP and automated Action

This is the verified detail steps on how to connect to Google assistant using gRpc. The following 3 environments have been tested:
Windows 10; 
Mac OSX mojave and 
Ubuntu 16.04 LTS.  

the customized action app has been verified from these 3 environments above
plus Samsung S8, 
Iphone X and 
Google Home Mini.

Samsung S8 we has also verified the Chinese version, but as the API/SDK is still under development preview stage, Chinese API is not yet released.

#### Please use Python 3.6 or lower to connect, we have verified the 3.7 will not work;

## for windows platform please following the instruction
project-aiy-voice-224701.txt
## for Mac platform please following the instruction
project-aiy-voice-224701-mac.txt
## for Linux or Rasberry Pi platform please following the instruction
project-aiy-voice-224701_Linux.txt

# main steps:

## 1. register a new project in Google and enable the api for google assistant;
## 2. create Oauth2 client_secret***.json 
## 3. use service to register the first device. (then the menu item will open up )
## 4. create the credential locally for execution
## 5. run the app or run the python code

### for app

googlesamples-assistant-pushtotalk --project-id aiy-voice-224701 --device-model-id aiy-voice-224701-prototype-light-v1

### for source code 

https://github.com/googlesamples/assistant-sdk-python.git

--for the source code:
https://github.com/googlesamples/assistant-sdk-python/tree/master/google-assistant-sdk/googlesamples/assistant/grpc

python -m pushtotalk --project-id aiy-voice-224701 --device-model-id aiy-voice-224701-prototype-light-v1



## customization 
### use the excel sheet to define questions and load in action to publish
### define the activation 
