# VMC_RM: AUTONAMER: NAMING CONVENTION CHECKER: SUBELEMENT, CATEGORY FUNCTION & CODE

> #### DESCRIPTION: 
- **Checks Room Naming if Following BEP NRM Codes (FINAL SCRIPT)**

> #### CHANGELOG:

| Latest Version | Log |
| :-------: | :----: | 
|[1.0.0] | [CHANGELOG](/_scripts/_project/263_VMC/ROOMS/changelog/VMC_RM_AutoNamer_NamingConventionChecker.md) |

> #### SCRIPT INFORMATION: 

| File Category| Associated Files | Dynamo Packages | Custom Packages | Dynamo Player Package| Revit Version | Author | Modified By | File Name & Location
| :-------: | :----: | :---: | :---: | :---: | :---: | :---: | :--: | :--:
| VMC_RM | VMC_RM_AutoNamer_SubElement & CategoryFunction | Clockwork 1.34.0 |  | 0_PACKAGE: 2_RM_AutoNamer_RoomCategoryCodes | Revit 2021.1 | Cathrine Macabuhay | | VMC_RM_AutoNamer_NamingConventionChecker
| | Excel Workbook from VMC_RM_AutoNamer_SubElement & CategoryFunction| BumbleBee 2021.25.3 | | | | | | (https://bimcapcom.sharepoint.com/:f:/s/BCP-Main/EtmeCVBVJRBDjXd4mcTyzAgBacqay7ie-Pv6y3dg9bDQ5w?e=GI3Hdf)



----------------------------------------------------------------
> #### SCRIPT: 
<img src="/_scripts/_project/263_VMC/ROOMS/images/VMC_RM_AutoNamer_NamingConventionChecker.png">


------------------------------------------------------------------------------

> #### DEMO: 
<video width="1280" height="720" controls>
 <source src="/_scripts/_project/263_VMC/ROOMS/demo/VMC_RM_AutoNamer_NamingConventionChecker.mp4" type="video/mp4">
</video>

#### INSTRUCTIONS: 
- **Please Install Packages First**
**PART 01 : ROOM AUTONAMER_SUBELEMENT, CATEGORY/FUNCTION & CODE**
- NOTE: **Subelement Dictionary**: HardCoded in the Script Itself.
- NOTE: **Category/Function Dictionary**: Values & Keys Taken from the Excel Dictionary Workbook.
- NOTE: **Code Value**: Taken from CAD Reference.
------------------------------------------------------------------------------
- *01: Import Exploded Room Code from CAD Reference*
- *02: Open Dynamo Player & Edit Inputs*
- *03: Assign Dictionary File Path for Category/Function*
- *04: Input Sheet Tab Name of the Dictionary for the Category/Function*
- *05: Assign Placeholder Workset Name (Can Delete This After the Script Has Run)*
- *06: Assign Excel Sheet Where Data for Missing Subelements, Category/Function, Codes will be Reported to for Checking*
- *07: Set Run Excel to True & Run the Script*
------------------------------------------------------------------------------
**PART 02 : AUTONAMER NAMING CONVENTION CHECKER: SUBELEMENT, CATEGORY FUNCTION & CODE**
- **Please Install Packages First**
- NOTE: This Script is Optional & Just Made for Secondary Checking After the AutoNamer Script.
------------------------------------------------------------------------------
- *01: Assign Same Excel File Path for Missing Subelements, Category/Function, Codes.*
- *02: Set Run Excel to True & Run the Script*