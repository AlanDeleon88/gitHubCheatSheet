
step by step process on how to start pair programming.
have a link for a more detailed doc with multiple git commands.

# Steps for the Driver:
## Step: 1 Find the project repo
  - Navigate to A/a repo page for problem set / project

![image](https://github.com/AlanDeleon88/gitHubCheatSheet/assets/92609467/23d4b31e-d5d0-4eef-938e-8ed26392b2e4)


## Step: 2 Clone the repo to your machine
   - Copy the repo url by clicking on the 'Code' button and copy the git url.
       ![image](https://github.com/AlanDeleon88/gitHubCheatSheet/assets/92609467/6752f20c-7b2d-49bf-b14a-c3abb1d5c754)

   - Navigate to folder where you want to clone the repo.
      ![image](https://github.com/AlanDeleon88/gitHubCheatSheet/assets/92609467/0b7438d8-620c-4b1a-9bab-af958397d565)

   - Run the command git clone in the terminal.
    ![image](https://github.com/AlanDeleon88/gitHubCheatSheet/assets/92609467/1290d842-b73c-466c-85b7-c3356eeccd3d)

   - Navigate to the folder where the repo was cloned.
     ![image](https://github.com/AlanDeleon88/gitHubCheatSheet/assets/92609467/754504f1-8166-4ad7-8790-f85d96bbf9d7)


## Step 3: Create your own repo for the project.
   - Click on the plus on the top left of the github page.
   ![image](https://github.com/AlanDeleon88/gitHubCheatSheet/assets/92609467/862e5d5d-8db5-45aa-98cc-a5248cbb1bd4)

   - Name repo and select owner as yourself, then set repo to private.
    ![image](https://github.com/AlanDeleon88/gitHubCheatSheet/assets/92609467/8e78a888-91c1-4337-8e0a-ba4d80e1b9dc)


## Step 4: Redirect cloned repo to your newly created repo
   - On your new repo page, copy the repo url.
        ![image](https://github.com/AlanDeleon88/gitHubCheatSheet/assets/92609467/71bb2b6e-cd93-4636-95d4-eb52a8e43496)
    - Back on the terminal, make sure you are in the folder you cloned the app academy repo in.
      Run the git command : 

       ```
           git remote set-url origin [YOUR REPO URL HERE]
       ```
   ![image](https://github.com/AlanDeleon88/gitHubCheatSheet/assets/92609467/61650088-70f6-4ca8-9b8b-d41b31aabae1)
   
   - Check to make sure the repo is now connected to your newly created repo by running the git command: 
      ```
        git remote -v
      ```
      ![image](https://github.com/AlanDeleon88/gitHubCheatSheet/assets/92609467/4328bbee-d3a4-491c-b943-f35ce50745d2)

   - Run git command: ```git add .```  to stage all the files in the folder.
   - Run git command: ```git push ``` to push all the files to the newly created repo.

- step 5 Invite pair programming partner as a collaborator.
    - navigate to settings for the git hub repo.
        -screenshot of settings button location
    - navigate to collaborators.
        -screenshot of collaborator ui
    - add partner's github username to collaborators.
        -screenshot of adding partner's username to collab for the repo

Steps for Navigator
- step 1 accept email invitation to the repo
    - show screenshot of email and accept collab screen
- step 2 clone partner's repo url
    - show where to find the repo url
    - show a screen shotof <git.clone [REPO URL]>
- step 3 change into project directory
    - show screenshot of terminal in user directory.

Work flow
- When it is time to switch roles the driver will push their code up to the shared repo.
    - run <git add .>
    - run <git commit -m "Commit message here"> its good practice to add a commit message that explains what changes were made to the code.
    - run <git push>
- Then the navigator will now run <git pull> and become the driver.
