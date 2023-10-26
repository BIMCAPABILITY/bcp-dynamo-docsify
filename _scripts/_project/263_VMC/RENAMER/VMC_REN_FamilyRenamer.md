# VMC_REN: FAMILY RENAMER

> #### DESCRIPTION: 
- **Checks Naming Convention in Accordance to VMT BEP for: System & Inplace Families, Materials, Linestyle, Filled Regions, Links**
- **Folder Created for Separate Renamer Script Checker per Category**

> #### CHANGELOG:

| Latest Version | Log |
| :-------: | :----: | 
|[2.0.0] | [CHANGELOG](/_scripts/_project/263_VMC/RENAMER/changelog/VMC_REN_FamilyRenamer.md) |

> #### SCRIPT INFORMATION: 

| File Category| Associated Files | Dynamo Packages | Custom Packages | Dynamo Player Package | Revit Version | Author | Modified By | File Name & Location 
| :-------: | :----: | :---: | :---: | :---: | :---: | :---: | :--: | :--: |
| VMC_REN | 0_PACKAGE: 1_Naming Convention & Renamer (Separated) | BumbleBee 2021.25.3| | | Revit 2021.1 |Cathrine Macabuhay | | VMC_REN_FamilyRenamer
|         |  | Clockwork 1.x 1.34.0| | | | | | (https://bimcapcom.sharepoint.com/:f:/s/BCP-Main/EsoDgNEM_W5HpCEI7KjA8BIB6x673ndlz01-eGqQ6ABqcA?e=8UWhY6)
|         |  | Crumple 2022.5.27   |
|         |  | Orchid 206.3.0.8161|
----------------------------------------------------------------
> #### SCRIPT: 
<img src="./_scripts/_project/263_VMC/RENAMER/images/VMC_REN_FamilyRenamer.png">

------------------------------------------------------------------------------

> #### DEMO: 

> #### 01. SYSTEM FAMILY | INPLACE FAMILY | MATERIALS | FILL PATTERN | FILL REGIONS | WORKSETS

<video width="1280" height="720" controls>
 <source src="./_scripts/_project/263_VMC/RENAMER/demo/VMC_REN_FamilyRenamer.mp4" type="video/mp4">
</video>

#### INSTRUCTIONS: 
- **Please Install Packages First**
- *01: Open Worksheet from previous Naming Convention Script - Duplicate "INCORRECT" Tab - Rename as "REVISED" and Rename all Incorrect Naming Conventions*
- *02: Open Dynamo Player : Select Script Folder Location*
- *03: Assign Excel Worksheet File Paths*
- *04: Run Script*
- *05: Script Automatically Renames Elements*
- *06: Script Will Export Secondary Naming Convention Checker into the Same Worksheet under a New Tab : "REVISED 02" for Anyother Naming Still Incorrect.*


> #### 02. LINESTYLE:

<video width="1280" height="720" controls>
 <source src="/_scripts/_project/263_VMC/RENAMER/demo/VMC_REN_FamilyRenamer_LineStyles.mp4" type="video/mp4">
</video>

#### INSTRUCTIONS [LINESTYLE]: 
- **Please Install Packages First**
- *01: Dynamo Player: Search for String to Rename and Assign Substitute*
- *02: Assign File Location of Previous Excel Sheet for LineStyle from Naming Convention*
- *03: Run Script*
- *04: Script Will Rename all [User Created] LineStyle Elements*
- *05: Script Will Export Secondary Naming Convention Checker into the Same Worksheet under a New Tab : "REVISED 02" for Anyother Naming Still Incorrect.*
