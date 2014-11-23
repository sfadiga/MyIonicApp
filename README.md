MyIonicApp
==========

A Ionic app Netbeans project template

This project is just a Netbeans Cordova project with Ionic framework added to it.

With this project you'll be able to modify the base project and deploy the Cordova application to both the emulator and your device.

For this project to work you'll need the followig installed on your computer:

* Netbeans 8.x (www.netbeans.org)  - It is recommended to download the Java EE version or the complete version.

* Cordova (or Phonegap) project (http://cordova.apache.org/)

* Ionic framework (http://ionicframework.com/)
	
After installing these projects you can download the MyIonicApp folder and open it on Netbeans. There you can change the App name and set other custom preferences. Done!

The Ionic app template used was the sidemenu template, if you want to use another project template here follow the steps to create your own project.
  
- Create a Ionic app with the desired name and template (here we create a tab template):

$ ionic start YourAppName tabs

- Create a Cordova project on Netbeans by using the HTML5 section and selecting Cordova, I recomend you create your project with the same name as above but on a different folder.

- Now we need to merge the contents of the Netbeans folder inside the Ionic app folder you've created. 

Copy the nbproject folder, platform, test and Do not override the config.xml and index.html inside the www folder. That's it!

Regards,
Sandro.
