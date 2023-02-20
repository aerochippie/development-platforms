
# FireBase

## Introduction

**Firebase** is a toolset for building applications and managing infrastructure built on top of **Google Cloud Platform**.  
It is one of the most popular **BaaS** services nowadays. Rather than writing both front-End and Back-End code,  
firebase helps to abstract a lot of the back-end functionality so the developers can focus on the applications experience itself.  
It provides services like _authentication, realtime databases, file storage, push notification, storage_ and more.  
All these are hosted in a cloud. It was founded by **James Tamplin** and **Andrew Lee**, due to its success and popularity it was eventually acquired by Google.  

## Brief History

- **2011** - Founded by James Tamplin and Andrew Lee originally as **Envolve** - a chat service
- **2012** - **Firebase** being launched as a separate company from **Envolve** to the public.
- **2014** - **Firebase Hosting** and **Firebase Authentication** being launched
- **2014** - **Firebase** acquired by **Google**.
-  Eventually a wide range of services have been added to firebase and it became one of the most popular BaaS services.

## Features

### **Realtime Database**

_**Firebase Realtime Database**_ (The Firebase´s original Database) and _**Cloud Firestore**_ (the newest DB for mobile app development) provide database services.  
These databases provide real-time updates to data/applications as it changes in the database.   
These are _cloud-hosted, NoSQL, JSON databases_ where data is synced in realtime and is available even when your application goes offline. Instead of typical HTTP requests, it uses data synchronization - every time data changes any connect device receives that update within a milisecond.

Firebase Realtime Database comes with a _expression-based rules language_ that you can use to define how you want your data to be structured, control read/write privileges or when the data is available and for whom.  

As it a **NoSQL** database it is a little different that a typical, relational database.  
The Realtime Database API only allows for operations that can be executed quickly - a great feature baling your application to be extremely responsive, but it does require a little bit of forethought and planning ahead while structuring the data.


### **Firebase Authentication**

Firebase supports authentication using _passwords, phone numbers, Google, Facebook and more_. It delivers industry standard like _Oauth and OpenID Connect_ which can be easily integrated with a custom backend.  
Firebase Authentication allows for secure logins which can be **really** difficult to implement correctly on your own.

### **Cloud Storage**

Cloud Storage provides a massively scalable file storage. The files are stored in a Google Cloud Storage _bucket_ which are accessible through both Firebase and Google Cloud.  
It scales automatically. It integrates with Firebase Authentication to identify users - providing a security language that you can use to set accesss control to data at the source. This way you can be sure that client can only access the data only in the ways you define.

### **Firebase hosting**

A secure global web hosting **CDN** for your web applications, which is really good at quickly delivering static and dynamic content using servers that are close to the users.  
Firebase also lets you connect **your own domain** name to a Firebase-hosted site. 
When using a _Firebase CLI_ you can deploy files from local directories to the hosting servers. There’s also a possibility to serve dynamic content and host microservices with the help of _Cloud Functions_ or _Cloud Run_. All this content is served over a **SSL connection**.

## Summary - Strengths and weaknesses  
The platforms **NoSQL** databases ensures that all data is safely stored, highly scalable and served in realtime.  
As web developers we want to focus on our application experience and ´exterior´. Firebase lets a front-end developer write as little back-end code as possible. This makes the entire development cycle **shorter, simpler and possibly cheaper**. Firebase has a very **wide range of services** and features and comes with a **free basic** plan so anyone can get started. 
Over a million applications have been created using **Firebase** - It provides an extensive technical documentation that makes it possible for total beginners to get a quick jumpstart.

Although Firebase has many strengths it does come with some issues. As it relies on a **flat data hierarchy** it is not made for processing **complex queries** like for example reversing order of certain items. Since it has a very **dynamic** data structure it cannot guarantee **data integrity** and eventually something may not be handled properly and the data will become messy.
