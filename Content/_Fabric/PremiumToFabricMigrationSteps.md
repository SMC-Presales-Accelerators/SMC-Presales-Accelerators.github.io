---
layout: page
title: Migrate your Power BI Workspace into Microsoft Fabric Capacity
---
This is a step by step guide walking you through moving your Power BI Workspace from being backed by a Premium capacity to a Fabric Capacity.

1.  Log into your Powerbi dashboard - [Power
    BI](https://app.powerbi.com/home?experience=power-bi)

    1.  Click settings \> navigate to **Admin Portal**

> <img src="./images/image1.png" style="width:1.82293in;height:4.00003in"
> alt="A screenshot of a phone Description automatically generated" />

2.  Click on **Capacity settings** then toggle to the **Fabric
    Capacity** tab

    1.  Click on the **Purchase** button to purchase a Fabric Capacity.

<img src="./images/image2.png" style="width:6.5in;height:3.45764in"
alt="A screenshot of a computer Description automatically generated" />

2.  Navigate to Azure Portal to complete the process of purchasing a
    Microsoft Fabric Capacity SKU.  
    <img src="./images/image3.png" style="width:5.19795in;height:4.69274in"
    alt="A screenshot of a computer Description automatically generated" />

3.  Go back to your PowerBI and you will notice the **Fabric Capacity**
    has been successfully provisioned.  
    <img src="./images/image4.png" style="width:6.5in;height:2.39861in"
    alt="A screenshot of a computer Description automatically generated" />

**Assign your PowerBI workspace to the new Fabric Capacity**

To migrate your Power BI and Fabric artifacts, you can simply reassign
your workspaces to the new Fabric capacity.

1.  Click on **Workspaces** on the left menu option

<img src="./images/image5.png" style="width:6.5in;height:2.33542in"
alt="A screenshot of a computer Description automatically generated" />

2.  Reassign workspaces to the new Fabric capacity(s) individually from
    each workspace or by bulk assigning them in the Admin Portal.

    1.  **Individually reassigning:** You can also assign a workspace to
        the newly created Fabric Capacity from the settings of that
        workspace. To move a workspace into a capacity, you must have
        admin permissions to that workspace, and also capacity
        assignment permissions to that capacity.

    2.  **Bulk assigning in the Admin Portal:** Admins, when managing a
        capacity in the admin portal, can see Workspaces assigned to
        this capacity section that allows you to assign workspaces to
        the newly created Fabric Capacity

<img src="./images/image6.png" style="width:6.5in;height:2.94028in"
alt="A screenshot of a computer Description automatically generated" />
