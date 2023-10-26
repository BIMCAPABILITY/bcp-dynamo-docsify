# 275_AE: NVO AREA PLANS

> #### DESCRIPTION: 
- **Creates NVO Area Plans**
- **Script Variations:**
- **A) Creates Area Boundary Lines and Places Areas**
- **B) Renames Area According to Room Name and Isolates "MK" & Areas <0.5sqm**
- - **v.3.0.0 Places Areas and Area Tags**

> #### CHANGELOG:

| Latest Version | Log |
| :-------: | :----: | 
| A) [3.1.0] | [CHANGELOG](/_scripts/_project/275_VESTEDA/AREA/changelog/AE_NVO.md) |
| B) [1.0.1] | 

> #### SCRIPT INFORMATION: 

| File Category | Associated Files | Dynamo Packages | Custom Packages | Dynamo Player Package | Revit Version | Author | Modified By | File Name & Location | 
| :-------: | :----: | :---: | :---: | :---: | :---: | :---: | :---: | :--: |
| 275_AE |  | archi-lab.net 2023.213.1523 | | 2_AE_AutoArea&AreaTags | Revit 2023 | Cathrine Macabuhay | Abjeet Singh | 1_NVO_v.3.0.0 |
|           |  | Wombat Dynamo V.2.3.5 |                 |                    | | | | (https://bimcapcom.sharepoint.com/:f:/s/BCP-Main/EpTSYF56d-dLuhMSF4Tstw8BF8kQsWPjHz8lDHeCSb9mgA?e=ZgD5kT) |
| | | Spring Nodes v210.1.1 |
| | | Crumple 2022.5.27 |
| | | Clockwork v.2.4.0 |
| | | Genius Loci 2023.7.13 |


------------------------------------------------------------
> #### SCRIPT: 

#### v.3.1.0
<img src="/_scripts/_project/275_VESTEDA/AREA/images/NVO_v.3.1.0.png">

#### A) NVO
<img src="./_scripts/_project/275_VESTEDA/AREA/images/275_AE_A_NVO.png">

#### B) BVO
<img src="./_scripts/_project/275_VESTEDA/AREA/images/275_AE_B_NVO.png">

------------------------------------------------------------

> #### DEMO: 

#### v.3.1.0
<video width="1280" height="720" controls>
 <source src="./_scripts/_project/275_VESTEDA/AREA/demo/NVO_v3.1.0.mp4" type="video/mp4">
</video>

#### INSTRUCTIONS: 
- Please Install Packages First
- Open Package Folder: 3_AE_BoundaryLines&AreaPlacements
----------------------------------------------------------------
#### NVO
- *01: Open Dynamo Player*
- *02: Click the Script Box to Edit Inputs*
- *03: Select Area Tag Family | Toggle to Run On/Off*
- *04: Type in Area View Comment*
- *05: Run the Script*

----------------------------------------------------------------

#### A&B)
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