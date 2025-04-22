## Creating a new project

1. New projects are created in Raspberry Pi Learning Admin 

1. Log in to [learning admin](https://learning-admin.raspberrypi.org/admin/projects) and go to the **Projects** tab

1. Select **‘New Project’**


![New Project](images/New_Project.png)


--- task ---

### Complete the following fields:

1. **Name:** Give your project a name, there are no rules regarding spacing, case etc in this field 
- e.g. **My New Project**

1. **Repository Name:** This must be in lower case and contain no spaces 
- e.g. **my-new-project**

1. **Ingredient:** These are little projects that sit within a main project, only tick this box if you will be using ingredients from other projects

1. **Featured:** Not currently used, leave blank

1. **Duration:** How long the project is, this is not really used so leave as 1

1. **Theme:** Not really used leave as it is

1. **List Fields:** These affect the dropdown options that are available in the **[Find a Project](https://projects.raspberrypi.org/en/projects)** bar on the Projects site
- Curriculum list
- Interest list
- Site Area list (not in use) 
- Hardware list add in lower case  - sense hat etc
- Software list add in lower case - scratch etc

1. **KPI list:** Select the KPIs that apply to this project, select/deselect multiple options with CMD or CTRL. This is used in the Looker Studio data analysis. The Pi option is used to separate out the Raspberry Pi projects as they are so popular. In this instance, for KPI select **Project Completions**

1. **Archived:** If a project is no longer useful this removes it from the **Find a Project** area but links to it will still exist for newsletters etc. A banner will appear to say don’t expect updates on this project and it becomes non searchable on the database

1. **Badge template:** Looks up graphics for badges

1. **Unskippable:** Was created purely for the safe-guarding module, no need to tick this

1. **Template:** Default

1. **Editor starter project:** If created in Code Editor type name in here 
- e.g. **my-new-project**

Changes or additions to the meta data can be added in later on if required.


![Project Fields 1](images/Project_1.png)
![Project Fields 2](images/Project_2.png)

--- /task ---


Once you  have filled in the fields above, press the **'Create Project'** button to create your project!


--- collapse ---

---

## Troubleshooting errors

---


### Errors when creating your project

When you press **‘Create Project’** you may find that this doesn’t work and you get an error message.


![Error Message](images/Error_Message.png)


This is an issue with the database and not something that you’ve done wrong. However, you now need to **delete this in the learning admin database and in GitHub** before starting the create a project process again.

### How to delete your project from the database  
- Go back to learning admin and click on ID to sort the list and get the newest created projects at the top


![Project ID](images/Projects_ID.png)


- Locate your project and press the red **‘Destroy’** button
- The ‘Destroy’ button always asks for confirmation
- Doing this only destroys the project in the database it doesn’t affect GitHub


![Destroy Button](images/Destroy_Button.png)


### How to delete your project from GitHub
- In your main GitHub account go to 'Settings'


![Settings](images/Settings.png)


- Choose 'Delete Repository'


![Delete Repository](images/Delete_Repository.png) 

--- /collapse ---


--- collapse ---

---

## What happens next?

---

- Once you have deleted the project from the learning admin database and GitHub, you need to begin the [create a project process again](step_2.md)
- Continue this until the project creates successfully and you don't receive an error message
- It may take a few times for this to work, remember to delete the failed project each time before starting again

--- /collapse ---