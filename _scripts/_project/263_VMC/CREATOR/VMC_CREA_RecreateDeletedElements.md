# VMC_CREA: RECREATE DELETED ELEMENTS

> #### DESCRIPTION: 
- **Recreates Deleted Elements by Point | Point & Host**

> #### CHANGELOG:

| Latest Version | Log |
| :-------: | :----: | 
|[1.0.0] | [CHANGELOG](/_scripts/_project/263_VMC/CREATOR/changelog/VMC_CREA_RecreateDeletedElements.md) |

> #### SCRIPT INFORMATION: 

| File Category| Associated Files | Dynamo Packages | Custom Packages | Dynamo Player Package | Revit Version | Author | Reviewed By | File Name & Location
| :-------: | :----: | :---: | :---: | :---: | :---: | :---: | :---: | :--:
| VMC_COLLR | Script: WA_OffAxisFixer | archi-lab 2023.213.1523 |  |  1_WA_OffAxis_HotFix (In 'WALLS' Category) -> 2.RECREATE METHOD | Revit 2021.1 | Cathrine Macabuhay| | VMC_CREA_RecreateDeletedElements
| | | RIE 2021.7.1 | | | | | | (https://bimcapcom.sharepoint.com/:f:/s/BCP-Main/Ess0Nz_rGjhKg3FsmkIBCigBenOH1xmGyoCNY5q7zalSXw?e=Fk65Sn)
----------------------------------------------------------------
> #### SCRIPT: 
<img src="/_scripts/_project/263_VMC/CREATOR/images/VMC_CREA_RecreateDeletedElements.png">


------------------------------------------------------------------------------

> #### DEMO: 

<video width="1280" height="720" controls>
 <source src="/_scripts/_project/263_VMC/COLLECTOR/demo/WA_OFFAXIS%20FIXER_RECREATE%20METHOD.mp4" type="video/mp4">
</video>

#### INSTRUCTIONS: 
- Please Install Packages First
- Open Package Folder: 1_WA_OffAxis_HotFix (In 'WALLS' Category)
----------------------------------------------------------------
STEP 1:
- *01: Open Dynamo Player*
- *02: Select the Folder Icon -> Select the Package File*
- *03: Dynamo Player Will Open All Scripts in the Package*
- *04: Click the Edit Inputs Icon for 1.VMC_WA_SlightlyOffAxisFixer (Script) -> Specify Excel File to Store the Information In*
- *05: Play 1.VMC_WA_SlightlyOffAxisFixer*
- *06: Allow 'Unjoin'and 'Delete' Elements*
---------------------------------------------------------
STEP 2: 
- *07: Click the Edit Inputs Icon for 2.GET ELEMENTS [POST RUN] -> Specify Same Excel File*
- *09: Play 2.GET ELEMENTS [POST RUN]* 
---------------------------------------------------------
STEP 3: 
- *10: Undo Run of Dynamo Script in Revit*
- *11: Click the Edit Inputs Icon for 3.[UNDO FIRST] GET ELEMENT PROPERTIES -> Specify Same Excel File*
- *12: Play 3.[UNDO FIRST] GET ELEMENT PROPERTIES*
---------------------------------------------------------
STEP 4:
- *13: Redo Run of Dynamo Script in Revit*
- *14: Click the Edit Inputs Icon for 4.[REDO FIRST] RECREATE ELEMENTS -> Specify Same Excel File*
- *15: Elements Deleted By Fixing Walls Off Axis Are Recreated*

----------------------------------------------------------------

#### NOTES: 
- All Scripts Use the Same Excel File 
- This Package is Used with the WA_OffAxisFixer
- 1.VMC_WA_SlightlyOffAxisFixer : Runs the Script as Usual
- 2.GET ELEMENTS [POST RUN] : Gets All Elements After Script Run [All Elements & Deleted Elements]
- 3.[UNDO FIRST] GET ELEMENT PROPERTIES : After Undoing Step 2., This Gets All Elements Before Deletion
- 4.[REDO FIRST] RECREATE ELEMENTS : Gets All Necessary Information to Recreate The Element.
