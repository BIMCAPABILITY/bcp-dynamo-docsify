# VMC_RM: SEPARATION LINE CREATION_CAD

> #### DESCRIPTION: 
- **Create Room Separation Line by Column Curves from CAD Links**

> #### CHANGELOG:

| Latest Version | Log |
| :-------: | :----: | 
|[2.1.0] | [CHANGELOG](/_scripts/_project/263_VMC/ROOMS/VMC_RM_SeparationLineCreation_CAD.md) |

> #### SCRIPT INFORMATION: 

| File Category | Associated Files | Dynamo Packages | Custom Packages | Dynamo Player Package | Revit Version | Author | Modified By | File Name & Location
| :-------: | :----: | :---: | :---: | :---: | :---: | :---: | :--: | :--:
| VMC_RM |  | spring nodes 210.1.1 | | | Revit 2021.1 | Jacky Luk | Bino Tuliao | VMC_RM_SeparationLineCreation_CAD
|  |  | archi-lab.net 2018.0.8 | | | | | Cathrine Macabuhay | (https://bimcapcom.sharepoint.com/:f:/s/BCP-Main/EtmeCVBVJRBDjXd4mcTyzAgBacqay7ie-Pv6y3dg9bDQ5w?e=GI3Hdf)
| | | BimorphNodes v.4.2.1/4.2.4 | | | | | 
| | | Clockwork v.2.4.0 |

----------------------------------------------------------------
> #### SCRIPT: 
<img src="./_scripts/_project/263_VMC/ROOMS/images/VMC_RM_SeparationLineCreation_CAD.png">


------------------------------------------------------------------------------

> #### DEMO: 
<video width="1280" height="720" controls>
 <source src="./_scripts/_project/263_VMC/ROOMS/demo/VMC_RoomSeparatorByCADLayer.mp4" type="video/mp4">
</video>

#### INSTRUCTIONS: 
- **Please check if there are prerequisites custom packages that are need to download before you run the script. 
You will be able to do that by opening the dynamo, then search for the custom packages on the "Packages" tab. 
With that, please install the following custom packages enumerated below which are being used specifically 
for this script:**
- *01: Open Dynamo Player*
- *02: Open the "Drawer" Looking Icon*
- *03: Input the Parameters Needed:*
    *[a]: Input the specific level of the imported CAD that you want to use.*
    *[b]:Then input the column layer name that you want to use as reference in generating the room separators.*
    *[c]: astly, input the core layer name that you want to use as reference in generating the room separators.*
- *04: Run the Script*