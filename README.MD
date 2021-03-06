HEAL-iOS APP
============
‘Uber for people in need of care’

#Inspiration:

We inspire to improve the life of people everywhere in the world with the help of compassionate caregivers. We feel, we can make this a world a better place for seniors and people in need of care to live a comfortable life and be respected in. Ultimately helping connect people who can help to those who need it the most. Whenever a person is in need, a caregiver is there to heed.
 
#Purpose:
Heal is platform for people in need of care, assistance and help to find people willing to help you through difficult times. Whether you are sick and home alone or you are a senior citizen who requires assistance to facilitate and make life easy, Heal provides a service to give you relief when it comes to this. Our goal is to create a uber-service for caregivers to reach out to people. Seniors, who fail to receive support from their family or live privately in an isolated place, but require extreme need and care during their feeble age, can use and benefit from this app extensively. Through this iOS app, whenever a person is experiencing moderate to strong illness, by typing in the symptoms, he/she is experiencing into the app; the nearest available caregiver available for attending to the situation would be contacted. The caregiver would be provided specific information regarding the symptoms the respective person is facing and the possible category of health disease the symptoms may possibly fall into.
   
#Documentation

- All View Controllers are in Views Group in Xcode
- There is only one target that is healapp
- Use pod file to update dependencies
- Run pod update to update your local forked repository to install dependencies
- Use xcsworkspace file to open project
- Swift 3 and iOS 10 dependency
- All View Controllers are in Views Group in Xcode
- There is only one target that is healapp
- Use pod file to update dependencies
- Run pod update to update your local forked repository to install dependencies
- Use xcsworkspace file to open project

#Contribution Guidelines

Please see detailed contribution guidelines in Contribute.MD in root folder

#Build/Deployment Guidelines

This is an Xcode Project with Pod dependency managemnt

1. Install cocoapods

			 	  gem install cocoapods

2. Install pods

			 	  pod update
    
3. Open file using .xcworkspace Xcode file    

4. Update any dependencies in .podfile
 

#How it was built

The caregiver would be provided specific information regarding the symptoms the respective person is facing and the possible category of health disease the symptoms may possibly fall into. For this hack, the information provided to the caregiver, was retrieved from IMO’s database through the use of their API. Using the api key provided by IMO, we were able to request authorization to access data from IMO’s database using specific health-tem keywords. The data obtained, was in the form of JSON (JavaScript Object Notation), and was infused into a REST API. This API was deployed in order to transmit data from the front-end to the back-end and vice versa. Our front-end was built in an iOS platform which is the User Interface for the customers and caregivers that use this app. The database and server for which the caregivers contacts and the customers accounts are stored is in: Firebase.     

#Challenges Faced
Requesting authorization from IMO to access their data in their database using the api key and api secret (IPL)
Implementing the REST API in flask
iOS?

#Features

Finding care takers around you:
Location based search for people willing to offer help to you
Firebase powered live tracking of people near you available to provide help to people in need
Matches you to the best fit in terms of treating your sickness/issues (Uses IMO API to find professionals who can treat your symptoms)
Easy on site service using Map integration

Quick Diagnosis and Summary

Professional caretakers like doctors, consultants and physicians will get a quick diagnosis of what the sickness might be.
They can get a quick profile of patient’s medical profile like allergies, medication taken, past history etc 

Communication facilities checking in with patients:
Messaging system for communicating emergency messages


#What we learned

Developing opensource project needs a lot more planning and modularizing to enable collaborative work on project in the future.

Opensource projects needs to be thoroughly documented to thrive as a free software.

It is not impossible to create a swift app that did something similar to Uber in under 36 hours.

A team can generate productivity through teamwork, hardwork and determination.



#Future for HEAL

We hope to bring this app into android and web platforms. We aim to bring this app globally into the market.

Future for heal is primarily reliant on it’s opensource essence of the app. We want contributors to extend the app in the ways of their own. Some of the exciting and interesting ideas people had on first review of our app during Hack Illinois 2017 are as follows:

Unit Testing of Existing Features
Use IMO code generated by API to add new features like:
Find remedies
Find local doctors or nurses
Use Disease Data to Display useful historical statistics for each patient for their caretaker
Add customized section for new types of users
Cooks and Chefs who want to cook food at home for sick/old people
Ordering Medicines/Prescriptions
Add Text to Order/Call to order Feature
Create a thorough document review process for professionals
Use Iot modules to monitor care-taker patients remotely and track their health, sleep etc

We have modularized the features within the app to ensure easy readable code and quickly start contributing to the project.

#Technologies used

- IMO API
- Firebase
- Real Time Database
- iOS 10
- Mapkit
- CoreLocation
- Python
- Django
- REST API

#Links
Swift Docuementation: https://developer.apple.com/library/prerelease/content/documentation/Swift/Conceptual/Swift_Programming_Language/

IMO Documentation (IPL):
https://ipldevelopers.e-imo.com/api/

Firebase Documentation:
https://firebase.google.com/docs/

Python Documentation:
https://docs.python.org/3/

#License

Our software is free to use and re-distribute. Please read license in License.md
