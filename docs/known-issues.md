# Tips And Known Issues

## Permission Set to Query All Files

If you are in a FileViewer component and think you may not be seeing all Files in your search criteria, that could be the case! You mmy need to give you or a sub set of your users a specific permission. 

NOTE: This permission can assigned to Users with View All Data permission and it will allow the user the ability to query ContentDocument and ContentVersion and retrieve all files in the org. Please be careful who you give this permission to 

In order to enable this follow the Salesforce article here: https://help.salesforce.com/s/articleView?id=000381258&type=1

## Salesforce Images Low Quality Render

### Occasionally Salesforce will render poor quality images of a document (for instance a pdf)

![Poor Quality Image](images/knownissues/imagequality/badrender.png)

Luckily Salesforce provides a way to regenerate images.

1. First we need to get the Content Document Id of the File
    - This can be done in a number of ways - the easiest is to use Salesforce's file image to open the modal window, navigate to view document and get the id from the url.
    - ![Find The Content Document Id](images/knownissues/imagequality/getcontentdocumentid.gif)
2. Give the content id to an administrator or a someone with access to setup.
3. From within the setup section
    1. Go to regenerate previews
    2. Enter the id and click 'Regenerate Preview'
    3. Wait a few minutes for the image to regenerate.


![Regenerate Images](images/knownissues/imagequality/regenerate-preview.gif)


### Using The Alternate Viewer

If using Google's Chrome browser window and you have permissions (check with your internal security officer first) you can use an extension such as:

<span style="font-size:larger;color:darkred; background-color:lightyellow">
***IMPORTANT! Firmworks does not support or endorse any browser extensions. The following extension does not publish security or privacy information and there for by installing it you are using it at your own risk!***</span>

- [PDF-Viewer](https://chrome.google.com/webstore/detail/pdf-viewer/oemmndcbldboiebfnladdacbdfmadadm/related?hl=en-US) to open pdf's in screen with FileViewer's Alternate Viewer button.

![Using Browser Extensions](images/knownissues/imagequality/browser-extension.gif)
