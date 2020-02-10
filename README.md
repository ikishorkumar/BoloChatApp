PROJECT REPORT

Bolo Chat App
Mobile Application Development (java)
      
      
Background:

Chat app is android based chat app that is widely used in the form of messengers WhatsApp, Facebook messenger, and etc. Bolo Chat app is used to interact/ engage with other user of the app, It’s the app where users can find new peoples, friends and engage with them easily and they can have new friends/ connections. Main reason to build this app is to provide the users an instant and secure app without any limitations of messages using internet so they can share greetings with their friends, family or colleges.

Introduction:

We have developed an android based Chat app named as Bolo App, it’s conversional app and greetings sharing app that is much similar to the WhatsApp that’s widely used today, as we have created this app for the semester project of mobile application development course so we have limited the functionalities of chat app to message and image sharing. In Bolo Chat App Users can interact/ engage with other users, app has Welcome Activity Page which have the two Buttons 
Already have an account and Need an Account, Users can send, receive, and cancel/decline the requests, also they can send messages, and pictures to other users to have good greetings with each other.

Key Objectives:

•	New User have to create An Account by clicking on Need an account button and filling up the Register form using given data format: name, email and password of 6 digit.
•	User that are already registered must click on Already have account button in the app and enter their registered correct username and password.
•	User that are old can login with the app using their registered username and password.
•	User can view the list of users of the application from all users in list menu.
•	User can change his profile image, account status from account setting in list menu.
•	User can Send, and Cancel the friend Request.
•	User can view all the requests from Request tab in menu.
•	User can view the add friends list form Friends tab in menu
•	User can logout form the app using logout tab in list menu
•	User can select the images from device to send or change the profile picture.

Tools:

We have used the latest tools and techniques so the app can be updated and runs perfectly.

•	Android Studio 3.5.2 
“Android Studio is the official integrated development environment for Google's Android operating system, built on JetBrains' IntelliJ IDEA software and designed specifically for Android development. It is available for download on Windows, macOS and Linux based operating systems”.

•	Firebase
“Firebase is a mobile and web application development platform developed by Firebase, Inc. in 2011, then acquired by Google in 2014. As of October 2018, the Firebase platform has 18 products, which are used by 1.5 million apps”.

•	Picasso 2.71 
“A powerful image downloading and caching library for Android - square/picasso. ... implementation 'com.squareup.picasso:picasso:2.71828' ”.

•	Image Cropper dependency that is used in it is: de.hdodenhof:circleimageview:3.0.1
“A fast circular Android-ImageView perfect for profile images.

It uses a BitmapShader and does not:
* create a copy of the original bitmap
* use a clipPath (which is neither hardware accelerated nor anti-aliased)
* use setXfermode to clip the bitmap (which means drawing twice to the canvas)

As this is just a custom ImaveView and not a custom Drawable or a combination of both, it can be used with all kinds of drawables, i.e. a PicassoDrawable from Picasso or other non-standard drawables (needs some testing though)”.


Java Files:

Java files are used for getter and setter of the related activities files.

•	Friends
“It’s a Java file that contains the getters and setters of the Friends Activity file”.

•	Users
“It’s a Java file that contains the getters and setters of the User Activity file”.

•	Messages
“It’s a Java file that contains the getters and setters of the Chat Activity file”.


XML Layouts:

XML files that are created to use for setting up the user view on particular fragments.

•	user_single_layout
“It’s a Xml layout file that is used for the view of a single User in friends and chat fragments”.

•	chat_custom_bar
“It’s a Xml layout file that is used for the view of Whole Conversion layout in Chat fragments”.

•	message_single_layout
“It’s a Xml layout file that is used for the view of message layout in Chat fragments”.

•	app_bar_layout
“It’s a Xml layout file that is used for the view of main bar in main activity and other activities in the app”.


Working Mechanism:

When applications start there are buttons sign in as “already have an account” and signup as “need an account”. If user clicks on sign up button, the sign-up form activity starts and user have to provide the information like email, password of 6 digit, and name and hit’s on sign up button, it processed and information is saved in firebase real time database and main activity starts.
If user clicks on sign in button then user have to enter the authenticated email and password and clicks on the sign in button, it processed and authenticated by firebase and starts the main activity, where three fragments named as friends, chats, requests and a menu shown, User can find 4 items in the menu from there user can logout, setting up profile details, and view all users. In this app three fragments are shown where user preform some activates like send and receive message, view friends list, view profile of users, and etc.

Firebase Database:

The Firebase Real-time Database is a cloud-hosted NoSQL database that lets you store and sync data between your users in real-time.

Firebase provides backend as a service. The service provides application developers an API that allows application data to be synchronized across clients and stored on Firebase's cloud.

Firebase has three core services: a real-time database, user authentication and hosting. With the Firebase iOS SDK, you can use these services to create apps without writing any server code

Storage Format
Data is stored in firebase as a large JSON document. It is the same case as it is done in most of the NoSQL database systems like MongoDB, Cassandra, CouchDB etc. The data is stored as a large object which can hold key value pairs where value can be a string, number or another object.
 
