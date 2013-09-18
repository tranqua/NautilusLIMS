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
##S102 Workflow Overview
Study 102 has 2 major workflows, Sample Collection and Tissue Collection.
__Mother Collection Overview__  
![][img_102_mother_sc]  
__Father/PFM Collection Overview__  
![][img_102_father_sc]  
__Newborn Collection Overview__  
![][img_102_nb_stc]  

##S102 Object Identifiers

##S102 Storage Options
Study 102 Aliquots in 2ml tubes can be stored in 10x10 boxes  
Study 102 PAXgene tubes can be stored in 7x7 boxes  
Study 102 CryoMold samples can be stored in 6x3 boxs  

10x10 boxes can be stored in *Racks* or *Canes*  in LN2 - there are several options depending on the rack configuration of the storage unit (1x5, 1x10, 1x12, 1x15)  
7x7 boxes can be stored in incubation areas, or in freezer (-20, -80) shelves  
6x3 boxes can be stored in a freezer (-80) or in a LN2 freezer.  

##S102 Processing Kits
Study 102 Kits can be made by the following steps:


The following kit layouts / contents will be available in Nautilus LIMS for Study 102. Kits should be used according to the samples collected.  

![][img_102_adult_kit_full]  
![][img_102_adult_kit_bs]  
![][img_102_adult_kit_u]  
![][img_102_adult_kit_s]  
![][img_102_nb_kit_full]  
![][img_102_nb_kit_b]  
![][img_102_nb_kit_tissue]  

##S102 Sample Collection
![][img_102_sample_wf]  
<form>
<input type ="checkbox">Locate a Study 102 Aliquot
<input type ="checkbox">Right Click > Build Plate
<input type ="checkbox">Select the workflow for the kit you wish to build
__TESTING NOTES__  
>Use the following plate workflows for Study 102 testing  
>Study 102 Adult Kit (Full) v0.2  
>Study 102 Adult Kit (Blood/Saliva)  
>Study 102 Adult Kit (Urine)  
>Study 102 Adult Kit (Saliva)  
>Study 102 Newborn Samples Kit  
>Study 102 Newborn (B/S) Samples Kit  
>Study 102 Newborn Tissue Kit  
<input type ="checkbox">Fill out the necessary information (plate barcode, location, tube barcodes) when prompted
</form>
##S102 Sample Processing


##S102 Tissue Collection
![][img_102_tissue_wf]  

##S102 Tissue Processing
##S102 Sample/Tissue Storage
##S102 Recollections
After a collection event has been documented, if anything happens to the sample/aliquots that results in the need for a recollection. The Lab Operator is expected to follow the current protocol and contact the necessary personnel. The Lab Operator also needs to document the recollection request in Nautilus LIMS.

#Study 104
##S104 Workflow Overview
##S104 Storage Options
##S104 Object Identifiers
##S104 Processing Kits
There is only 1 processing kit available for Study 104. The layout and content is as follows:  
![][img_104_kit]  

Locate any __Study 104__ aliquot in the system using the explorer window. Right Click on the item and navigate to __Build__ > __Plate__  
![][img_build_plate]  
The Plate Login window will apprear, select the __Study 104 Kit__ from the dropdown options and click __OK__  
![][img_104_build_kit]  
A new window will appear, prompting you for the __Plate Barcode__ and the __Location ID__  
![][img_104_login_kit]  
After filling out those items, click __OK__ which will then prompt you to scan in the barcodes in this kit.  
![][img_104_scan_bc]  
Scan in the barcodes and click OK.  

##S104 Sample Collection
##S104 Sample Processing
##S104 Sample Storage


[icon_box]: http://i.imgur.com/I6z4agl.png

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

[img_102_mother_sc]: http://i.imgur.com/WQ0fDR5.png
[img_102_father_sc]: http://i.imgur.com/W3gPPZZ.png
[img_102_nb_stc]: http://i.imgur.com/hBxu3xJ.png
[img_102_sample_wf]: http://i.imgur.com/A0v1i6u.png
[img_102_tissue_wf]: http://i.imgur.com/duwsaTF.png
[img_102_adult_kit_full]: http://i.imgur.com/Ms5z9i9.png
[img_102_adult_kit_bs]: http://i.imgur.com/jNWRvQF.png
[img_102_adult_kit_u]: http://i.imgur.com/C8uKNxA.png
[img_102_adult_kit_s]: http://i.imgur.com/pEWnx8h.png
[img_102_nb_kit_full]: http://i.imgur.com/otry2N4.png
[img_102_nb_kit_b]: http://i.imgur.com/6W5IKUj.png
[img_102_nb_kit_tissue]: http://i.imgur.com/EflO6tc.png


[img_104_build_kit]: http://i.imgur.com/L69pQKt.png
[img_104_login_kit]: http://i.imgur.com/oK9sYp9.png
[img_104_scan_bc]: http://i.imgur.com/5g0pqMq.png
[img_104_kit]: http://i.imgur.com/nqfZVXv.png


