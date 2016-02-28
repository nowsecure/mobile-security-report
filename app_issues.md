## App issues

Here we provide a high-level summary of the security of mobile apps, based on our in-depth app vulnerability findings which are explained in the “Detailed App Vulnerability Findings” section of this report.

We define leaky apps as mobile applications that transmit or store private user information in an insecure manner. Security failures might include man-in-the-middle vulnerabilities and insecure data transmission or storage. Intentionally or not, legitimate apps can collect and transmit location, device identifiers, personal contacts, and more. 

We define high risk security flaws as issues that expose data that a malicious individual could use to gather private, sensitive information and/or monitor a user’s activity.

In our analysis of more than 400,000 apps available from the Google Play store:
* 10.8% of all apps leak sensitive data over the network
* 24.7% of mobile applications have at least one high risk security flaw
* 50.0% of popular apps send data to an ad network including but not limited to phone numbers, IMEI number (a unique identifier assigned to cellular devices), call logs, location coordinates, and more
