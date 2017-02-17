---
layout: post
title: BlocChat
thumbnail-path: "img/blocchat.png"
short-description: Build a chat application that uses Firebase to send and recieve messages in real time.

---

{:.center}
![]({{ site.baseurl }}/img/blocchat.png)

## Explanation

This was by far one of my favorite applications to build.  With using a messaging application throughout the day at work, it was interesting to see how some of the basic features worked together to create the chat room experience.

## Problem

With using the Angular JS framework for building the project, Firebase had to be registered as a module in the application.  It would then be necessary to inject the $firebaseArray service in a controller and implement methods of the Firebase JavaScript and AngularFire API's.  

## Solution

Created the controllers and their services in order to query a Firebase array.  Implemented UI Bootstrap to create a modal to create new chat rooms, as well as create a new user.  Also, each room was selectable in order for the associated content.  Finally, implemented the use of cookies to store the information in the user's web browser.

## Results

 Testing also implemented the use of Grunt for this project, as well as debugging in the console.  Some of my initial challenges was due to understanding how to successfully implement the Firebase database with the correct set-up to allow for successful querying of the data.  After I overcame that challenge, the development process went smooth.  

> **Learning Point -** Got a taste of implementing an external database with a taste of debugging any querying issues.  Also, this application allowed me to get practice using data binding and practice when and when not to utilize $scope throughout the project. 

## Conclusion

Upon completion of BlocChat, I had built a simple messaging application that could create a new user, new chat rooms, and send messages, which were linked to the user with a timestamp.  This project also helped to solidify my understanding and implementation of Angular.