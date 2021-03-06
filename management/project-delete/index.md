---
title: Project Deletion
permalink: /management/project-delete/
---

It is possible to entirely delete your project. 

To do so, go to **Users & Settings** and select the **Settings** tab. Then click the **Delete Project** button. 
The project deletion actually only marks a project for deletion and, for some time, does no other changes to it. 

{: .image-popup}
![Screenshot - Project Delete](/management/project-delete/project-delete.png)

Once the project is marked for deletion, it enters a **60-day grace period** during which it cannot 
be accessed and all project operations, such as data loads and orchestrations, are stopped.

During the grace period, a request for undeleting the project can be sent to our [Support](mailto:support@keboola.com). 
However, the deletion will become irreversible after the time expires, and the project along with any associated data will be gone for good.

We strongly suggest you make a [backup of your project](/management/project-export/) before deleting it. 

## GoodData Projects
If the KBC project has provisioned a GoodData project, that project will also be deleted. The grace 
period for a GoodData project is **5 days**. When a GoodData writer is deleted, the associated project
is deleted after the grace period. When a KBC project is deleted (but the GoodData writer was left in it), 
the associated GoodData project will be deleted in 5 to 14 days from the deletion of the KBC project.

**Important**: Expiring projects will be deleted **automatically** when the expiration day is due. 
You will receive a **notification** a week in advance. 
When an expired project is deleted, the same grace period rules will apply as if it was deleted manually.  
