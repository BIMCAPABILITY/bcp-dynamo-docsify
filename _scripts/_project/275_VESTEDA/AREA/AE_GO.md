# 275_AE: GO AREA PLANS

> #### DESCRIPTION: 
- **Creates GO Area Plans**
- **Two script Variations**
- **A) Creates Area Boundary Lines and Places Areas - Gets Both Floor SLab Outline and Interior Structural Walls**
- **B) Creates Area Boundary Lines and Places Areas - Gets Only Floor SLab Outline Only**

> #### CHANGELOG:

| Latest Version | Log |
| :-------: | :----: | 
| A) [2.0.0] | [CHANGELOG](/_scripts/_project/275_VESTEDA/AREA/changelog/AE_GO.md) |
| B) [1.0.0] | 

> #### SCRIPT INFORMATION: 

| File Category | Associated Files | Dynamo Packages | Custom Packages | Dynamo Player Package | Revit Version | Author | Reviewed By | File Name & Location | 
| :-------: | :----: | :---: | :---: | :---: | :---: | :---: | :---: | :--: |
| 275_AE |  | archi-lab.net 2023.213.1523 | | 1_ AE_BoudaryLines&AreaPlacements |Revit 2023| Cathrine Macabuhay |  | 20230601_275_AE_A_GO V2.0.0 |
|           |  | WombatDynamo V.2.3.5 |                 |                    | | | | 20230601_275_AE_B_GO V1.0.0 |
| | | Spring Nodes 210.1.1 | | | | | | (https://bimcapcom.sharepoint.com/:f:/s/BCP-Main/Ep-67CzejlBPhYoGnRRkW88BkADxZLWiKNiGEavmM2eZJg?e=SEg7sx) |


------------------------------------------------------------
> #### SCRIPT: 
#### A) GO
<img src="./_scripts/_project/275_VESTEDA/AREA/images/275_AE_A_GO.png">

#### B) GO
<img src="./_scripts/_project/275_VESTEDA/AREA/images/275_AE_B_GO.png">

------------------------------------------------------------

> #### DEMO: 

#### A) GO
<video width="1280" height="720" controls>
 <source src="./_scripts/_project/275_VESTEDA/AREA/demo/275_AE_A_GO.mp4" type="video/mp4">
</video>

#### INSTRUCTIONS: 
- Please Install Packages First
- Open Package Folder: 1_AE_BoundaryLines&AreaPlacements
----------------------------------------------------------------
- *01: Open Dynamo Player*
- *02: Click the Script Box to Edit Inputs*
- *03: Select Level*
- *04: Set Area Name [GO]*
- *05: Select Area Plan View*
- *07: Run Script*
- *08: GO Area Boundaries and Areas Are Placed Automatically*
------------------------------------------------------------

#### B) GO
<video width="1280" height="720" controls>
 <source src="/_scripts/_project/275_VESTEDA/AREA/demo/275_AE_B_GO.mp4" type="video/mp4">
</video>

#### INSTRUCTIONS:
- Please Install Packages First
- Open Package Folder: 1_AE_BoundaryLines&AreaPlacements
----------------------------------------------------------------
- *01: Open Dynamo Player*
- *02: Click the Script Box to Edit Inputs*
- *03: Select Level*
- *04: Set Area Name [GO]*
- *05: Select Area Plan View*
- *07: Run Script*
- *08: GO Area Boundaries and Areas Are Placed Automatically*
------------------------------------------------------------

#### SUPPLEMENTARY SCRIPT: AE_DELETE_REDUNDANT
<video width="1280" height="720" controls>
 <source src="/_scripts/_project/275_VESTEDA/AREA/demo/AE_Delete_Redundant.mp4" type="video/mp4">
</video>

#### INSTRUCTIONS:
- Please Install Packages First
- Open Package Folder: 1_AE_BoundaryLines&AreaPlacements
----------------------------------------------------------------
- *01: Open Dynamo Player*
- *02: Click the Script Box to Edit Inputs*
- *03: Click "Select"*
- *04: Select Areas to be Deleted*
- *05: Click Finish in the Revit Workspace*
- *07: Run Script*
- *08: Areas are Deleted*
------------------------------------------------------------

> #### NOTES: 
#### A) GO : Retrieved Both Wall Slab Outline (Offset) & STR Interior Walls to be Isolated, Sets Area Boundary Lines and Areas
- for A) GO : Just Clean up the Area Boundary Lines. Areas Should Enclose, any Redundant or Un-needed Areas Maybe Deleted using the Supplementary Script in the Dynamo Player Package : "AE_Delete Redundant"

#### B) GO : Retrieves only Wall Slab Outline (Offset), Sets Area Boundary Lines and Areas
- Slab Floor Outlines Set to "EXT" & "INT" Accordingly and Separated.
- Append "EXT" & "INT" to Type Name