# Eclipse
This section will walk you through using Maven tooling for running and debugging your app within Eclipse. If you have not already installed m2e in Eclipse, you will want to do so now.

To install the Maven tooling, use the following steps:

1. Go to the Eclipse Marketplace under the Help menu in Eclipse.
![Eclipse Marketplace](eclipse1.png)

2. In the Find dialog enter the phrase Maven and hit enter.
![Eclipse Marketplace](eclipse2.png)

3. Find the Maven Integration for Eclipse plugin and click the Install button for that entry.
![Eclipse Marketplace](eclipse3.png)
4. Accept the defaults by clicking Next , and then accept the User License Agreement to begin the installation.

## Import UFtasks Project

Once you have completed the installation of the prerequisites from the previous section, you will now be able to go ahead and import the Maven project you created in the first section of this guide.

Follow these steps to get the project setup:

1. From the File menu, select Import…
![eclipse import](eclipseImport1.png)
2. You will be presented with the Import dialog box. From here you want to select Maven → Existing Maven Projects
![eclipse import](eclipseImport2.png)
3. From the Import Maven Projects dialog, you will need to select the directory location of the project you created in the first section of this guide. In the Root Directory field of the dialog, enter the path to the project, or click Browse… to select it from the file chooser dialog.
![eclipse import](eclipseImport3.png)
4. Click Finish to begin the import process.
5. When the import process has finished, you should see your project imported within the Eclipse Project Explorer.
![eclipse import](eclipseImport4.png)


##Running UFTasks with Eclipse

1. Next you will need to setup a Maven Run Profile for UF tasks. To do so select Run As… > Maven Build…
![eclipse run](eclipseRun1.png)
2. Edit the configuration, and your goals should be: clean gwt:run
![eclipse run](eclipseRun2.png)
3. Now, click on Run or Debug Button:
![eclipse run](eclipseRun3.png)
4. Wait for GWT build and run, and then click on Launch default Browser button:
![eclipse run](eclipseRun4.png)
5. See the result in your browser:
![eclipse run](eclipseRun5.png)
