# 275_AE: NVO AREA PLANS

> #### DESCRIPTION: 
- **Creates NVO Area Plans**
- **Two Part Script:**
- **A) Creates Area Boundary Lines and Places Areas**
- **B) Renames Area According to Room Name and Isolates "MK" & Areas <0.5sqm**

> #### CHANGELOG:

| Latest Version | Log |
| :-------: | :----: | 
| A) [1.0.0] | [CHANGELOG](/_scripts/_project/275_VESTEDA/AREA/changelog/AE_NVO.md) |
| B) [1.0.1] | 

> #### SCRIPT INFORMATION: 

| File Category | Associated Files | Dynamo Packages | Custom Packages | Dynamo Player Package | Revit Version | Author | Reviewed By | File Name & Location | 
| :-------: | :----: | :---: | :---: | :---: | :---: | :---: | :---: | :--: |
| 275_AE |  | archi-lab.net 2023.213.1523 | | 1_ AE_BoudaryLines&AreaPlacements |Revit 2023| Cathrine Macabuhay |  | 20230522_275_AE_A_NVO V1.0.0 |
|           |  | WombatDynamo V.2.3.5 |                 |                    | | | | 20230601_275_AE_B_NVO V1.0.1 |
| | | Spring Nodes 210.1.1 | | | | | | (https://bimcapcom.sharepoint.com/:f:/s/BCP-Main/Ep-67CzejlBPhYoGnRRkW88BkADxZLWiKNiGEavmM2eZJg?e=SEg7sx) |
| | | Rhythm V.2023.4.2024 |

------------------------------------------------------------
> #### SCRIPT: 
#### A) NVO
<img src="./_scripts/_project/275_VESTEDA/AREA/images/275_AE_A_NVO.png">

#### B) BVO
<img src="./_scripts/_project/275_VESTEDA/AREA/images/275_AE_B_NVO.png">

------------------------------------------------------------

> #### DEMO: 

<video width="1280" height="720" controls>
 <source src="./_scripts/_project/275_VESTEDA/AREA/demo/275_AE_NVO.mp4" type="video/mp4">
</video>

#### INSTRUCTIONS: 
- Please Install Packages First
- Open Package Folder: 1_AE_BoundaryLines&AreaPlacements
----------------------------------------------------------------
#### A) NVO
- *01: Open Dynamo Player*
- *02: Click the Script Box to Edit Inputs*
- *03: Type in Comment*
- *04: Select Level*
- *05: Select Area Plan View*
- *06: Run the Script*
- *07: NVO Area Boundaries and Areas Are Placed Automatically*

#### B) NVO
- *01: Open Dynamo Player*
- *02: Click the Script Box to Edit Inputs*
- *04: Select Level*
- *05: Select Area Plan View*
- *06: Run the Script*
- *07: NVO Areas are Renamed According to Room Names,"MK", <0.5sqm Areas Filtered and Isolated*

------------------------------------------------------------
> #### NOTES: 
#### A) NVO
- Some Areas Will be Placed in the Middle of Elements, Just Adjust Them Accordingly.
- Make Sure "K" Rooms are Non-Room Bounding.