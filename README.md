# React-Native-web-to-apk
convert any website or url  to mobile app using react-native

# Setting up the native development environment documentation
https://reactnative.dev/docs/environment-setup

# Webview Libraries
react-native webview
https://github.com/react-native-webview/react-native-webview/blob/master/docs/Getting-Started.md

# Documentation
after creating native cli app youl will go to your project directory
root folder then android/create new file named local.properties then add this lines

 //this is your android sdk path
sdk.dir=C:\\Users\\username\\AppData\\Local\\Android\\Sdk 

//java jdk path
org.gradle.java.home=C:\\Program Files\\Java\\jdk-15.0.1   
then save and run npx 'react-native run-android'

# Run url to webview code
now you need to remove all the code from your project folder/app.js then add this follwing codes given the link:<br>
https://github.com/faheem-cmd/react-native-webview-app.js

then save and run react-native run-android




