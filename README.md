## Android Phonegap Email Composer Plugin

  * Author: Tanin Srivaraphong (Original : Guido Sabatini)
  * Contributor: Ayyappa Veerapaneni
  * License: The MIT License
  * Supports only PhoneGap/Cordova 3.x.x and above.


## Installation
```javascript
cordova plugin add https://github.com/acveer/cordova-android-emailcomposer-plugin.git 

## Uninstallation
```javascript
cordova plugin remove org.apache.cordova.email

## Callable interface:

```javascript
window.plugins.emailComposer.showEmailComposerWithCallback(callback,subject,body,toRecipients,ccRecipients,bccRecipients,isHtml,attachments);
```

OR

```javascript
window.plugins.emailComposer.showEmailComposer(subject,body,toRecipients,ccRecipients,bccRecipients,isHtml,attachments);
```




## Parameters

    callback: never used
    subject: a string representing the subject of the email; can be null
    body: a string representing the email body (could be HTML code, in this case set isHtml to true); can be null
    toRecipients: a js array containing all the email addresses for TO field; can be null/empty
    ccRecipients: a js array containing all the email addresses for CC field; can be null/empty
    bccRecipients: a js array containing all the email addresses for BCC field; can be null/empty
    isHtml: a bool value indicating if the body is HTML or plain text
    attachments: a js array containing all full paths to the files you want to attach; can be null/empty

