Android Facebook Login with phone gap
=====================

This is the demo for Facebook Login in Apache Cordova/PhoneGap!

----------

Set up the Facebook SDK for Android:
---------
- Install the Facebook SDK for Android and the Facebook APK from here: (https://developers.facebook.com/docs/android/getting-started)

- Import the Facebook SDK into Eclipse 

- Link the Facebook SDK library to your project. View the properties for the project, and navigate to the 'Android' tab. In the lower part of the dialog, click 'Add' and choose the 'FacebookSDK' project from the workspace.
How to Use
---------
1) Clone this repo on your Machine 
2) Import the application to your workspace 

 - **File > Import > Android > Existing Android Code Into Workspace >**
 - **Browse.. >**
 - **Navigate to the path where you have cloned the project**
 - click **OK**

3)To use this plugin you will need to make sure you've registered your **Facebook app with Facebook** and have an **APP_ID** (https://developers.facebook.com/apps).

4)Add **YOUR_APP_ID** in html.xml file into your application's **assets/www** folder.

5) Configure the URL whitelist in the **res/xml/config.xml**  file, you can allow all domains with (set to this by default):

  **<  access origin="*" />**
  
6) Add a new **com.facebook.LoginActivity** activity to your app to handle Facebook Login. Open up your **AndroidManifest.xml** file and add this additional activity:

> < activity android:name="com.facebook.LoginActivity"
         android:label="@string/app_name" />
        

Clean build your Project and run it on your device.

![enter image description here][1]
 


![enter image description here][2]


![enter image description here][3]


![enter image description here][4]


  [1]: https://lh6.googleusercontent.com/-QxkZd231P0U/UwGs1nsyc2I/AAAAAAAAAAs/nKXn_TiU_e0/s0/capture_08.png "loginusercapture_08.png"
  [2]: https://lh3.googleusercontent.com/-uDmV3Y1XzvA/UwGtB-c2XHI/AAAAAAAAAA4/fXgeGHDgmeA/s0/capture_09.png "usernamePassword9.png"
  [3]: https://lh6.googleusercontent.com/XO1WxTGSroC2L42VKxeeYYTA-Tl9w3n24XyFhbq8_Q=s0 "after"
  [4]: https://lh5.googleusercontent.com/-FRbT-6eHVJ8/UwGvVkOt4LI/AAAAAAAAAB4/-1yxexhoxtk/s0/capture_11.png "capture_11.png"