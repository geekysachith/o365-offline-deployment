# o365-offline-deployment
Office 365 ProPlus is available in a 32-bit and a 64-bit version. I recommend that you deploy the 32-bit version, even on computers that have 64-bit operating systems. If you think you need the 64-bit version, carefully review the information about 64-bit editions of Office before you deploy. If users install from the Office 365 portal, be sure to tell them which version to install. 
Step 1
Download the newly released version of the Office 2016 Deployment Tool. (Download Link - http://www.microsoft.com/en-us/download/details.aspx?id=49117&WT)

Step 2
Run the Office 2016 Deployment tool, extract the files.

Step 3
Download the o365 Configuration file and edit the configuration.xml file which will be located in the extracted file of Office Deployment.

Step 4
Download the media:
Open a command window and change the directory to the location of your setup.exe file. Run setup /download configuration.xml

Step 5
After the Office software is downloaded to your network, you can copy the setup package in a USB disk and copy it to another computer, then run the following command to start the installation: Setup.exe /configure configuration.xml.

Step 6
Activate your o365 product by signing with an o365 Subscribtion account.
