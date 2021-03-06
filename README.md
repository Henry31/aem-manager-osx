wcm.io AEM Manager for Mac OS X
===============================

Taskbar application for managing AEM instances on Mac OS X.

There is also a version for Windows:
https://github.com/wcm-io-devops/aem-manager


Overview
---------

The AEM manager is a Mac OS X application that allows to manage local AEM instances for AEM developers. It allows to start, stop instances in the menubar. Via menubar quick links are available to the most important entry points.


Installation
------------

* Download the latest release from the [Releases](https://github.com/petermannel/aem-manager-osx/releases) section.
* Install DMG File to your Applications Folder. The DMG File is not signed, so enable GateKeeper for App-Download from anywhere in your security settings.

Tested with OS X 10.11 El Capitan.


Features
--------

After starting the AEM manager a table with the instances is shown:

![AEM Manager on Startup](/images/aem-manager-startup.png)

You can define new instances:

![AEM Instance](/images/aem-instance.png)

The main menubar icon offers a context menu with some global useful links, and the possible to choose for which instances a separate icon should be displayed in the taskbar:

![AEM Manager Context Menu](/images/aem-manager-context-menu.png)

For each instance icon a context menu offers to start/stop the instance, open log files or open a browser to jump into different entry points:

![AEM Instance Context Menu](/images/aem-instance-context-menu.png)

Known Bugs
----------

* No JProfiler Support
* Some java args seems not supported by NSTask()


Issue Tracking
--------------

For bugs and enhancement requests please file a ticket at https://wcm-io.atlassian.net/projects/WDEVOP
