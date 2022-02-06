Introduction
<p>Welcome to News Hour documentation & thank you for buying our product. So there are
two setup steps here. Admin panel & App. Both are developed on Flutter. So, You have to
install flutter on your computer. You can use Both Visual Studio Code & Android Studio
for Flutter. The steps are the same for both IDE.. We have used Visual Studio Code. So, Our
Setup will be based on this IDE.</p>

1. Flutter Installation
First, You have to install flutter on your computer. To install flutter on your computer,
follow the official documentation from Google.
Flutter Official Site : https://flutter.dev/.
You can follow these youtube videos to install flutter also.
1. For Mac: https://www.youtube.com/watch?v=9GuzMsZQUYs
2. For Windows: https://www.youtube.com/watch?v=T9LdScRVhv8
Make sure you have installed the latest stable version of flutter. If everything is okay then
you can follow the further steps below.

2. Admin Panel Setup
After successfully installing Flutter on your computer, You have to enable Flutter web
support. Make sure you have installed the stable channel.

.1 Flutter Web Setup
From Flutter stable version 2.0.0+, it will support the web. So, If you are already on the
latest stable channel of flutter, you don’t have to do anything for the flutter web. You
should run all the commands on your IDE terminal from the project directory.
1. Open the source/news_admin folder with your terminal and wait some moment to
load the admin project.
2. After that run the following command to clean the whole project

flutter clean


3. After that run the following command to get the required packages.

flutter pub get

4. After that run the following command to enable web support for your project.

flutter config --enable-web

And then it will enable the web feature for your project. That’s it. Your admin project
initialization is complete

2.2 Firebase(Database) Setup for Admin Panel :
1. We have used the firestore database as the backend for this project. First go to the
Firebase Console and sign in with your gmail account and go to the console.
2. Create a project by your app name. And go to the project overview.
3. Click on the plus icon and then click on the web icon. You will see a popup like the
second picture below :
![image](https://user-images.githubusercontent.com/3023249/152670593-8773de3d-ee38-4e49-bd8f-9259dd4e79ee.png)



