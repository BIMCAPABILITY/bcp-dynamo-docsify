# JGC_SUP: DUCT HANGER PLACER

> #### DESCRIPTION: 
- **Place Hanger (Supports) - Duct System**

> #### CHANGELOG:

| Latest Version | Log |
| :-------: | :----: | 
|[1.0.0] | [CHANGELOG](/_scripts/_project/268_JGC/SUPPORTS/changelog/JGC_SUP_PipeHangerPlacer.md) |

> #### SCRIPT INFORMATION: 

| File Category | Associated Files | Dynamo Packages | Custom Packages | Dynamo Player Package | Revit Version | Author | Reviewed By | File Name & Location | 
| :-------: | :----: | :---: | :---: | :---: | :---: | :---: | :---: | :--: |
| JGC_SUP |  | Wombat Dynamo v.1.3.2 |  |  | Revit 2020.2.9 | Bino Tuliao | | JGC_SUP_DUCTHangerPlacer |
|           |  | archilab.net v2022.212.3121 |                 |                    | | | | (https://bimcapcom.sharepoint.com/:f:/s/BCP-Main/EkUV1F95ULtFqMGB22mN7NIBKRhWmEfSulEqbucyJO3M9w?e=RQBIIA) |
| | | BimorphNodes v.4.2.4 | 
| | | GeniusLoci v.2023.2.21 |

----------------------------------------------------------------
> #### SCRIPT: 
<img src="/_scripts/_project/268_JGC/SUPPORTS/images/JGC_SUP_DUCTHangerPlacer.png">
----------------------------------------------------------------

> #### DEMO: 

<video width="1280" height="720" controls>
 <source src="/_scripts/_project/268_JGC/SUPPORTS/demo/JGC_SUP_DUCTHangerPlacer.mp4" type="video/mp4">
</video>

#### INSTRUCTIONS: 
##### Open Package Folder: 2_Wall Protection Package

- *01: Load the Generic Family that will be used for the Opening*
- *02: Run the Dynamo Player*
- *03: Open the "Drawer" Looking Icon*
- *04: Provide the Requirements:*
    - *Load the Required Hanger Family*
    - *Specify:*
        - *Minimum Duct Length*
        - *Start/End Inset (Of Hanger)*
        - *Target Spacing (for Hanger)*
        - *Duct Offsets (Sides & Bottom) if require*
    - *Specify (if changed):*
        - *Parameter Names*
    - *Select A Single Duct:*
        - *It will Automatically get All the Ducts Involved Under the Selected Ducts System Name.*