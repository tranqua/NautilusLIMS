Nautilus LIMS User Guide
=============
Nautilus is a central laboratory information management system (LIMS) service for Inova Translational Medicine Institute (ITMI) at Inova Health System. The system will facilitate the tracking and management of specimens, laboratory inventories, and reagent ordering; the management of lab and QC data; the acquisition of data directly from instruments; and the exchange of laboratory results data. 

User Guide Document
-----------
The purpose of this user guide document is to provide instruction for ITMI lab operators to complete the necessary tasks for sample management for studies built in Nautilus LIMS

References
----------
End-users may reference the following documents for further details on the Nautilus LIMS application and any extensions.
Documents may be found in the ITMI Share Drive.


The Basics
==========
##Loggin In to LIMS
###Accessing the Application
LIMS is a stand-alone application and must be installed on each computer that is used to access the system. Users can find the application by clicking on the Nautilus icon on their desktop. 
If that’s not available, the application can also be accessed by:
>Windows XP
Click on “Start” > Programs > Nautilus > Nautilus

>Windows 7
Click on "Start" > All Programs > Nautilus > Nautilus

###Configuring Your Database
The first time you fire up the LIMS application you’ll be prompted to enter Logon Information  
![Logon Information][img_logon]

If the __Server__ field is blank, cancel out of the window

Locate the following icons on the top left of the application and click on the __Server Setup__ icon  
![][img_serverSU]

A new window will appear, click on the __Import__ icon  
![][img_serverImport]

Locate the __LIMS_servers.xml__ file in the ITMI Share Drive (LAB\LIMS\Configuration Files). Click __OK__ after locating and selecting the file.

Now you can log in by clicking the __Login__ icon  
![][img_login]

##LIMS Interface
Nautilus LIMS utilizes a windows based interface for viewing dynamic data entities and navigating through the workflows.
###Lab Operator Toolbar
The ITMI Lab Operator Tool bar is a tool bar set that’s made specifically for the lab operators. Upon log-in, the tool bar can be found in the top of the application window.  
![][img_toolbar]
>If the toolbar is not there by default, users can find it by Right Clicking on the gray bar at the top of the application window and select __ITMI Lab Operator__  
>![][img_toolbar_LO]

#####Toolbar Overview
![][img_toolbar_list]  

Toolbar Icon | Description
--- | ---
__Enhanced Explorer__ | The main interface for browsing LIMS data. More details about the Enhanced Explorer can be found in the Nautilus Configuration Guide (Page 27)
__Refresh__ | Refresh the data on the screen.
__Login Sample__ |	Opens up the prompt to log in a new sample
__Login Plate__ | Opens up the prompt to log in a new plate (boxes only)
__LM Availability__ | Location Management Extension – used to find available slots
__LM Find Aliquot__	 | Location Management Extension – used to locate an aliquot by barcode
__LM Find Location__ | Location Management Extension – used to locate a specific location in the system by name
__LM Find Plate__ | Location Management Extension – used to locate a plate by barcode
__Location Folder__ | Opens up the folder of all the locations in LIMS

###LIMS Explorer

###LIMS Entities

#Lab Functions
##Create Storage Boxes
Storage boxes can be created using the Plate Login icon ![][img_plate_icon]
In the Plate Login window, slect from the drop-down menu the storage box you'd like to create for your study and click __OK__.  
![][img_plate_login_window]  
A new window will appear, enter the prompted information and click OK to create the box.

NOTE: Storage boxes still need to be moved to the necessary storage locations after creation. 

##Location Management
##Create Storage Location

#Study 102
##Workflow Overview
##Storage Options
##Processing Kits
##Sample Collection
##Sample Processing
##Tissue Collection
##Tissue Processing
##Sample/Tissue Storage

#Study 104
##Workflow Overview
##Storage Options
##Processing Kits
Locate any __Study 104__ aliquot in the system using the explorer window. Right Click on the item and navigate to __Build__ > __Plate__
![][img_build_plate]
The Plate Login window will apprear, select the __Study 104 Kit__ from the dropdown options and click __OK__  
![][img_104_build_kit]
A new window will appear, prompting you for the __Plate Barcode__ and the __Location ID__  
![][img_104_login_kit]
After filling out those items, click __OK__ which will then prompt you to scan in the barcodes in this kit.  
![][img_104_scan_bc]
Scan in the barcodes and click OK.
##Sample Collection
##Sample Processing
##Sample Storage




[img_logon]: http://i.imgur.com/48oaspS.png
[img_serverSU]: http://i.imgur.com/aOMfWoJ.png
[img_serverImport]: http://i.imgur.com/w8sSI6X.png
[img_login]: http://i.imgur.com/6y5eLjc.png

[img_toolbar]: http://i.imgur.com/mxO2EJB.png
[img_toolbar_LO]: http://i.imgur.com/D0vIR55.png
[img_toolbar_list]: http://i.imgur.com/r8RkisY.png

[img_plate_icon]: http://i.imgur.com/HBgpPhb.png
[img_plate_login_window]: http://i.imgur.com/y1feW5E.png
[img_build_plate]: http://i.imgur.com/oecyKpg.png

[img_104_build_kit]: http://i.imgur.com/L69pQKt.png
[img_104_login_kit]: http://i.imgur.com/oK9sYp9.png
[img_104_scan_bc]: http://i.imgur.com/5g0pqMq.png
