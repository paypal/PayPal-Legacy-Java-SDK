# PayPal Legacy Java SDK

### PayPal Legacy Java SDK JSP Sample

##### Steps to run the PayPal Java SDK JSP Sample:
- Download and install the Java SDK 1.8 and Apache Tomcat 5.x or above.
- Copy the [sample paypaljsp.war](https://github.com/paypal/PayPal-Legacy-Java-SDK/blob/master/sample/paypaljsp.war) file to your Tomcat `webapps` folder (`<TOMCAT ROOT>/webapps/`).
- Restart Apache Tomcat.
- Using Tomcat's default configuration running on your local machine, to access the PayPal Java SDK JSP Sample homepage, open the following URL: [http://localhost:8080/paypaljsp/soap](http://localhost:8080/paypaljsp/soap)
- Select the default API Sandbox account, or enter your own API credentials.
- The PayPal log file (`paypal-jsp.log`) will be created under `<TOMCAT ROOT>/logs/`

##### Note
- The sample WAR file includes `paypal_base.jar` which is part of the PayPal Java SDK. To run this sample application, you do not need to replace your current `paypal_base.jar` unless it is on the Java classpath or OS path. The sample web application will normally load the `paypal_base.jar` inside the WAR under most web container classloader rules. However, if you get any error, please try replacing your current `paypal_base.jar` with the one in the WAR file to ensure there is not a class loading issue.


### Updating your SDK
Replace [paypal_base.jar](https://github.com/paypal/PayPal-Legacy-Java-SDK/blob/master/paypal_base.jar) in the PayPal Java SDK directory with the one in this repository.  `[paypal_base.jar](https://github.com/paypal/PayPal-Legacy-Java-SDK/blob/master/paypal_base.jar)` can be used for both SOAP and NVP integrations.

Contributing
------------

Please read our [contributing guidelines](CONTRIBUTING.md) prior to submitting a Pull Request.

License
-------

Please refer to this repo's [license file](LICENSE).