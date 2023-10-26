# PDP_WA: FILTER WALLS >3000MM

> #### DESCRIPTION: 
- **Isolates Walls in View Over 3000mm - Isolate View and Category & Set View Range for Selection**

> #### CHANGELOG:

| Latest Version | Log |
| :-------: | :----: | 
|[1.0.0] | [CHANGELOG](/_scripts/_project/272_PDP/WALLS/changelog/PDP_WA_Above.md) |

> #### SCRIPT INFORMATION: 

| File Category| Associated Files | Dynamo Packages | Custom Packages | Dynamo Player Package | Revit Version | Author | Modified By | File Name & Location |
| :-------: | :----: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| PDP_WA |  | archi-lab.net 2023.213.1523| | 1_Wall Comments | Revit 2022 | Cathrine Macabuhay |  | PDP_WA_FilterWalls_Above 3000mm |
|         |  | Genius Loci 2022.7.5| | | | | | (https://bimcapcom.sharepoint.com/:f:/s/BCP-Main/EkUV1F95ULtFqMGB22mN7NIBKRhWmEfSulEqbucyJO3M9w?e=CvfinB)|
----------------------------------------------------------------
> #### SCRIPT: 
<img src="/_scripts/_project/272_PDP/WALLS/images/PDP_WA_Above.png">
----------------------------------------------------------------

> #### DEMO: 

<video width="1280" height="720" controls>
 <source src="/_scripts/_project/272_PDP/WALLS/demo/PDP_WA_CommentsFilter.mp4" type="video/mp4">
</video>

#### INSTRUCTIONS: 
- **Please Install Packages First**
**PDP Wall Scripts are to be used in Dynamo Player by order:**

      - 01: [01] Run Walls Filter >3000mm
      - 02: [00] Run Wall Comments [Set Comment]
      - 03: [02] Run Walls Filter <3000mm
      - 04: [00] Run Wall Comments [Set Comment]
------------------------------------------------------------------
Open Dynamo Player 
- *01: Open Dynamo Player & Open PDP Scripts File Path Location*

01. Isolate Walls Above 3000mm
- *01: Open Edit Inputs [Isolate Walls Above 3000mm]*
- *02: Select View To Filter from Drop Down and Run*

02. Assign Wall Comments for Walls Above 3000mm
- *01: Open Edit Inputs [Wall Comment]*
- *02: Input Comment into Text Box*

03. Isolate Walls Below 3000mm
- *01: Open Edit Inputs [Isolate Walls Below 3000mm]*
- *02: Select View To Filter from Drop Down and Run*

04. Assign Wall Comments for Walls Below 3000mm
- *01: Open Edit Inputs [Wall Comment]*
- *02: Input Comment into Text Box*
------------------------------------------------------------------
<img src="/_scripts/_project/272_PDP/WALLS/images/PDPPlayer.png" 
     width="550" 
     height="400" />
