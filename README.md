QlikView Extension - WebPageViewer2
===

QlikView Extension to display a web page in QlikView.

This is a replacement for the WebPageViewer extension which is installed as one of the extension examples when installing QlikView 11.

Features
--------

Basically this only fixes one bug of the WebPageViewer extension and adds some new features in comparison to the default WebPageViewer-extension:

* **Bugfix for multiple instances of WebPageViewer on one sheet**  
The standard WebPageViewer extension does not allow to place multiple instances of the extension on one sheet.

* **New Feature: Prevent Interaction**  
If this option is ticked the user will not be able to interact with the web page loaded in the extension (e.g. clicking on links, etc.)

* **New Feature: Prevent Reloading Url**  
If the Url does not change (e.g. when making some selections in QlikView) the web page will only be refreshed if the setting `Prevent reloading if Url does not change` is set to `false`.

Screenshots
-----------

**Adding the WebPageViewer2 Extension:**  
  ![Adding the WebPageViewer2 Extension](https://raw.github.com/stefanwalther/QlikView_Extension_WebPageViewer2/master/gh-pages/images/WebPageViewer2_AddExtensionObject.png)


**Configuration Dialog:**  
  ![Configuration Dialog](https://raw.github.com/stefanwalther/QlikView_Extension_WebPageViewer2/master/gh-pages/images/WebPageViewer2_PropertyDialog.png)


Installation & Configuration
----------------------------

1. Download the extension
1. Install the extension on your local computer (doubleclick on the .qar file)
1. Drag'n'Drop the extension within QlikView Desktop (using WebView)
1. Set the desired properties:
   * Set the web page Url
   * Define whether interaction with the loaded web site should be prevented or not
1. Finally deploy the extension to your server (-> [detailed instruction](http://www.qlikblog.at/1597/qliktip-40-installingdeploying-qlikview-extensions/))


Resources
---------
* [Change Log](https://github.com/stefanwalther/QlikView_Extension_WebPageViewer2/blob/master/CHANGELOG.md)
* Additional information can be found at http://www.qlikblog.at/2679/improved-webpageviewer-qlikview-extension
* [Direct download](https://github.com/stefanwalther/QlikView_Extension_WebPageViewer2/raw/master/Install/WebPageViewer2_Latest.qar) of the latest build


License & Credits
-------
The software is made available "AS IS" without any warranty of any kind under the MIT License (MIT).
Since this is a private project QlikTech support agreement does not cover support for this software.

For further license related information please [go to license page](https://github.com/stefanwalther/QlikView_Extension_WebPageViewer2/blob/master/LICENSE.md)

