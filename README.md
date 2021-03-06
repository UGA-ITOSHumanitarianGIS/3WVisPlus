# 3WVisPlus
Visualizations with COD, 3W plus Context 

Viewing COD mapped features in context of humanitarian operational sectors is useful for planning response. 

Several platforms enable visualization work including PowerBI, Tableau and Qlik. ITOS supports visualization effort for UN OCHA. A Qlik option with preloaded map data (kml format) highlights desktop capability and options for customizations. ITOS demonstrates two applications, one a base template focused at the country context and an example application which shows some interesting depictions through graphs and charts and maps of custom data. The [template](https://github.com/UGA-ITOSHumanitarianGIS/3WVisPlus/raw/master/Apps/iso_hxl_qlik_template_v11_MLI.qvf) is updated with more robust browsing capability. The earlier **Qlik Mali Prototype** available through HDX here:
https://data.humdata.org/dataset/qlik-sense-template-cod-mli will be updated in early 2020.

For information on how to load [DEEP](https://beta.thedeep.io/) into the Qlik Mali Prototype -or any Qlik Sense Desktop app, see the [Wiki](https://github.com/UGA-ITOSHumanitarianGIS/3WVisPlus/wiki). Here are details on the Qlik prototype:
Keep in mind, this is one product under development. 

## Operating Environment
Tablet (running Windows 10), Laptop, Desktop, An Internet Connection is required to log in to Qlik Sense and once an application is loaded, there should be no internet connection needed if an application is stored locally with adequate permissions to files for a period of time. The saved authentication lasts for 10 days before a prompt to log in again.

## Design and Implementation
Must have connectivity to download source.

•	Must have an operating environment to run Qlik Sense Desktop: http://help.qlik.com/en-US/sense/June2019/Subsystems/Hub/Content/Sense_Hub/Introduction/install-desktop.htm#anchor-1

•	Must have an account with Qlik or your organizations Qlik server 

## User Documentation
Documentation for the product is bundled with the installation. When the application is loaded, a sheet labelled “Introduction” includes some guided instructions for the application.
Additionally, a webinar is under development for the product and individual files for instructions include:
How to Extract COD zip File.docx
How to Reconfigure Data Connection.docx

## Assumptions and Dependencies
•	System architecture to run the application

•	A Qlik account

•	Qlik Sense Desktop

•	User must have basic computer device operation knowledge

•	A file downloaded from HDX with ITOS as a source and labelled “Qlik Sense Template” with a qvd extension is the product requiring online capability. 

•	A zip file downloaded from HDX with ITOS as a source labelled “Qlik Sense Template” contains all data and application template files, including the file with the qvf extension which is essentially the application. This also includes instructions for linking the data in the application for complete offline capability with the data. The application and features may still work with networked data, however if there is no connectivity available, the application will show the visualization. 

•	If the user is in a disconnected environment, some features of Qlik Sense Desktop may be unavailable.

•	The data loaded in the application are static and timestamped. It is up to the user whether the application is offline or connected, to verify the provenance, timeliness and applicability of the data. This may be done with HDX in the case the source is from HDX. 

•	A Qlik visualization application, or file with a .qvf extension, may contain a load script as to provide quick start features and allow for data conventions needed to display the information. Users may modify this to meet their needs. It us up to users to understand the Qlik load processes and functions as they are applied to datasets and support may be found on the Qlik site to do this. 

•	The application allows users to modify components of a visualization. These may include sheets, application meta information. It may be a good practice in use of this product to keep a copy, or simply add data and new sheets and modify the added sheets as necessary to keep the original state of the quick start features intact. 

