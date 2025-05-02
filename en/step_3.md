## Project notifications

Every time you build a project or make updates you will be notified in the **#project-notifications** slack channel. 

Some projects take more time to build than others, especially if there are a number of translations as each translation also has to be rebuilt. If your notification takes some time to appear this is likley the reason why.

Below are examples of messages or errors you may receive, what they mean and actions to take.


--- task ---

### Project created successfully

- Once your project has successfully been created a notification will appear in the **#project-notifications** slack channel
- Open the link in that channel to see the draft project template
- Your project is now set up and you can begin to write it in VS Code!

![Project Notification](images/Project_Notification.png)

--- /task ---


--- task ---

### Project failed to build

- If there is an error within the project it will fail to build and you will be notified in the **#project-notifications** slack channel

![Project Failed To Build](images/Build_Fail.png)

- On the notification click the **check the issues** link
- This will open the issue in GitHub where you can find more detail and see what needs to be fixed
- Once you have fixed the problem, close the issue in GitHub to clear it

![GitHub Error Message](images/GitHub_Error.png)

![Close Issue Button](images/Close_Issue.png)


--- /task ---


--- task ---

### Rate limits exceeded

- There are **rate limits** for GitHub and Amazon that can occasionally stop the build process
- You will be notified at what time the rate limit is refreshed

![Rate Limits Notification](images/Rate_Limits.png)

--- /task ---