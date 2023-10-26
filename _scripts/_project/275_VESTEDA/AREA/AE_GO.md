# 275_AE: GO AREA PLANS

> #### DESCRIPTION: 
- **Creates GO Area Plans**
- **Script Variations:**
- **A) Creates Area Boundary Lines and Places Areas - Gets Both Floor Slab Outline and Interior Structural Walls**
- **B) Creates Area Boundary Lines and Places Areas - Gets Only Floor Slab Outline Only**
- **v.3.0.0 Places Areas and Area Tags**

> #### CHANGELOG:

| Latest Version | Log |
| :-------: | :----: | 
| A) [3.0.0] | [CHANGELOG](/_scripts/_project/275_VESTEDA/AREA/changelog/AE_GO.md) |
| B) [1.0.0] | 

> #### SCRIPT INFORMATION: 

| File Category | Associated Files | Dynamo Packages | Custom Packages | Dynamo Player Package | Revit Version | Author | Modified By | File Name & Location | 
| :-------: | :----: | :---: | :---: | :---: | :---: | :---: | :---: | :--: |
| 275_AE |  | Data Shapes v.2022.2.105 | | 2_AE_AutoArea&AreaTags | Revit 2023 | Cathrine Macabuhay |  | 3_GO_v.3.0.0 |
|           |  | Wombat Dynamo V.2.3.5 |                 |                    | | | | (https://bimcapcom.sharepoint.com/:f:/s/BCP-Main/EpTSYF56d-dLuhMSF4Tstw8BF8kQsWPjHz8lDHeCSb9mgA?e=ZgD5kT) |
| | | Spring Nodes v210.1.1 |
| | | Genius Loci v.2023.2.21 | 
| | | Clockwork v.2.4.0 |
| | | Crumple v.2022.5.27 |
| | | archi-lab.net 2023.213.1523 |
| | | MEPover v.2022.1.1 |


------------------------------------------------------------
> #### SCRIPT: 

#### v.3.0.0
<img src="/_scripts/_project/275_VESTEDA/AREA/images/GO_v.3.0.0.png">

#### A) GO
<img src="./_scripts/_project/275_VESTEDA/AREA/images/275_AE_A_GO.png">

#### B) GO
<img src="./_scripts/_project/275_VESTEDA/AREA/images/275_AE_B_GO.png">

------------------------------------------------------------

> #### DEMO: 

#### v.3.0.0
<video width="1280" height="720" controls>
 <source src="./_scripts/_project/275_VESTEDA/AREA/demo/GO_v.3.0.0.mp4" type="video/mp4">
</video>

#### INSTRUCTIONS: 
- Please Install Packages First
- Open Package Folder: 3_AE_BoundaryLines&AreaPlacements
----------------------------------------------------------------
- *01: Open Dynamo Player*
- *02: Click the Script Box to Edit Inputs*
- *03: Select Area Tag Family*
- *04: Toggle On/Off to Run Tag Placement*
- *05: Set Area Name*
- *07: Run Script*
- *08: Area Boundary Lines, Area Placement, Area Tags are placed & Organizing Category_2, Unit Address are Automatically Filled*

----------------------------------------------------------------

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