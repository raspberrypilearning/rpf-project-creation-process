## Creating a new project

New projects are created in Raspberry Pi Learning Admin. 

1. Log in to [learning admin](https://learning-admin.raspberrypi.org/admin/projects) and go to the Projects tab.

1. Select ‘New Project’


![New Project](images/New_Project.png)


### Complete the following fields:

1. **Name:** Give your project a name, there are no rules regarding spacing, case etc in this field e.g. My New Project

1. **Repository Name:** This must be in lower case and contain no spaces e.g. my-new-project

1. **Ingredient:** These are little projects that sit within a main project, only tick this box if you will be using ingredients from other projects

1. **Featured:** Not currently used, leave blank

1. **Duration:** How long the project is, this is not really used leave as 1

1. **Theme:** Not really used leave as it is

1. **List Fields:** These affect the dropdown options that are available in the ‘Find a Project’ bar on the Projects site
- Curriculum list
- Interest list
- Site Area list (not in use) 
- Hardware list add in lower case  - sense hat etc
- Software list add in lower case - scratch etc

1. **KPI list:** Select the KPI(s) that apply to this project (select/deselect multiple options with CMD or CTRL). This is used in the Looker Studio data analysis (the Pi option is used to separate out the Raspberry Pi projects as they are so popular) in this instance for KPI select **Project Completions**

1. **Archived:** If project no longer useful this removes it from all projects area but links to it will still exist for newsletter etc. A banner will appear to say don’t expect updates etc and it becomes non searchable on database

1. **Badge template:** Looks up graphics for badge

1. **Unskippable:** Was created purely for the safe-guarding module, no need to tick

1. **Template:** Default

1. **Editor starter project:** If created in Code Editor type name in here e.g. my-new-project

This meta data can be added immediately or added in if needed, later on.


![Project Fields 1](images/Project_1.png)
![Project Fields 2](images/Project_2.png)


## Troubleshooting

### Errors when creating your project

When you press ‘Create Project’ you may find that this doesn’t work and you get an error message.


![Error Message](images/Error_Message.png)


This is an issue with the database and not something that you’ve done wrong. However, you now need to **delete this in the learning admin database and in GitHub** before starting the create a project process again.

### How to delete your project from the database  
- Go back to learning admin and sort by ID
- Locate your project and press ‘Destroy’
- The ‘Destroy’ button always asks for confirmation
- Doing this only destroys the project in the database it doesn’t affect GitHub

### How to delete your project from GitHub
- In your main GitHub account go to 'Settings' and choose 'Delete Repository'


![Settings](images/Settings.png)

![Delete Repository](images/Delete_Repository.png)


### What happens next?
- Once you have deleted the project from the learning admin database and GitHub, you need to begin the create a project process again
- Continue this until the project creates successfully and you don't receive an error message
- It may take a few times for this to work, remember to delete the failed project each time before starting again
- Once your project has successfully been created a notification will appear in the **#project-notifications** slack channel
- Open the link in that channel to see the draft project template
- Your project is now set up and you can begin to write it in VS Code!


![Project Notification](images/Project_Notification.png)
