# Mobile Application Penetration Testing Comprehensive Guides

# Mobile applications require testing within a number of distinct phases:

Security testing on a standard device (e.g. iOS or Android) – by default an iOS or Android device includes restrictions that prevent users from accessing privileged accounts (e.g. iOS is a Unix-like operating system therefore root provides full access). This phase should identify issues that are present irrespective of the device the application is deployed on.

Security testing on device with privilege escalation (e.g. ‘jailbreaking’ - where a vulnerability exists within the underlying iOS kernel) which enables the testing to be conducted with full root access to the device.

The purpose of utilising this exploit is to uncover the true nature of data stored and processed on the device. Additional code can be inserted into the running application designed to interfere with the program’s usual control of processing.

Reviewing source code to further understand exploitable vulnerabilities – whilst the source code should be kept secure and typically attackers will not have access, providing access to the full source code provides URM with the ability to review the code for potential vulnerabilities and look to exploit these within the application.
