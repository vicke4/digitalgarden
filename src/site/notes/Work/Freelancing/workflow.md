---
{"dg-publish":true,"dg-permalink":"workflow","permalink":"/workflow/"}
---

# Workflow
This document will give an overview of your workflow once the apps are built successfully. To solve the problems stated [on the document shared](https://docs.google.com/document/d/1mE5er1zjdZ5NH9xa5XhB6Irt0G35ejhzAxCoT5Pdguk/edit) with me, we will need three different apps,

 1. Linx log reader app - will be installed on the machines operating printer machines.
 2. QC app - will be installed on QC employees system
 3. An webapp to analyse & visulaize the data collected by the above 2 apps.

1 & 2 will be a desktop app which needs manually installation on devices.
3 will be a webapp that you can access from any device with an internet connection & a browser.

I will brief below how each app will work together to acheive the goal.

## Linx log reader app
After installing the app, one need to input the passcode generated by the webapp mentioned below to login to the app.

After logging-in, the user need to set the location of the dryer log & generic log if it's different from the default ones. Once the user sees an "Reading logs" alert on the device, they need to select their name from the dropdown (More about this on the webapp section).

Now, the app will send timestamp data along with the piece ID, machine ID, emplyee name to the webapp as soon as there's a new entry in the dryer log file.

When the print machine is handed over to a different employee, they have to open this app & set their name from the dropdown.


## QC app
After installing the app, one need to input the passcode generated by the webapp mentioned below like the log reader app to login to the app.

After logging-in, they need to select their name from the dropdown (More about this on the webapp section).

As soon as a QC employee scans the barcode, they will be asked to select one or more checkbox from a list (One can use the webapp to add the list of options available) and submit.

We can also display the employee name associated with the piece on the screen if needed.

## Webapp
This will act as a control center of all activity. You can use it from any device with an internet connection & a browser.

You can login to the webapp from an URL (will be decided & shared soon) using your Google account.

After logging-in, the user will get access to an alphanumeric string which they can use to login to the above two apps.

Here, there are three primary things the user need to do,
   1. Updating the list of print maching operating employee names.
   2. Updating the list of QC employee names.
   3. Giving a name to machine IDs 
	   - Unique machine IDs will be displayed on the above two apps.
	   - You can give a human readable name to those machine IDs from the webapp.
	   - This helps in easily identifying the faulty/maintenance needed machines.

All analytics, reports generated from the data collected from the above two apps will be available in this app. 

You can also cast this on a TV at your office :)

Now, you can know the [[cost-estimation | cost estimate]].