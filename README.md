# PayPal-Legacy-Java-SDK

### PayPal Legacy Java SDK JSP Sample

##### Steps to run the PayPal Java SDK JSP Sample:
- Download and install the Java SDK 1.8 and Apache Tomcat 5.x or above.
- Copy the [paypaljsp.war](https://github.com/paypal/PayPal-Legacy-Java-SDK/blob/master/paypaljsp.war) file to your Tomcat webapps folder (<TOMCAT ROOT>\webapps\ ).
- Restart Apache Tomcat.
- Using Tomcat's default configuration running on your local machine, to access the 
  - PayPal Java SDK JSP Sample homepage, open the following URL:
  - http://localhost:8080/paypaljsp/soap
- Select the default API Sandbox account, or enter your own API credentials.
- The PayPal log file (paypal-jsp.log) will be created under <TOMCAT ROOT>\logs\

##### Note
The sample war file includes `paypal_base.jar` which is part of the PayPal Java SDK. To run this sample application, You do not need to replace your current `.jar` with it unless it is on Java classpath or OS path because the application will load the one inside it. However, if you get any error, you might need to replace your current `.jar`.



### PayPal Legacy Java SDK
Please replace [paypal_base.jar](https://github.com/paypal/PayPal-Legacy-Java-SDK/blob/master/paypal_base.jar) in the PayPal Java SDK directory with the one in this repository.
