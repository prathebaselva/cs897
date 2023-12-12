- Step 1: Set Up the Project
  - User1 : Create bare remote repository
  - ![alt text](bare_remote_repo.png)
- Step 2: Open terminal and cd to location to clone the remote github repository
- Step 3: Clone to local machine
  - User1 and User2: Clone repo to local machine
  ```git clone https://github.com/<username>/mnist_classification.git```
  - ![alt text](clone.png)
  - [Hear the clone command](https://github.com/prathebaselva/cs897/assets/38529810/4f1d2e77-79ba-4c0f-aa2f-721239c76151)

- Step 4: Create branches
  - User 1 : create branch1 from remote repo
    ```git checkout -b user1-branch```
  - User 2 : create branch2 from remote repo
    ```git checkout -b user1-branch```
  - ![alt text](branch.png)
  - [Hear the branch command](https://github.com/prathebaselva/cs897/assets/38529810/de1b16f9-e778-461e-ac9c-83ebba3d2bcc)

** Steps to create the project files**
- Step 5: Create to Commit
  - Step 5.1: User1 - Create a Neural Network model file
    - ``` vi model.py```
  - Step 5.2: User1 - Add model file to repository
    - ``` git add model.py ```
  - Step 5.3: User1 - Check status (optional)
    - ``` git status ```
    - This should show that the model.py file as been added and the changes are yet to be committed
  - Step 5.4: User1 - Commit gthe file
    - ``` git commit -m "model file added" ```
  - Step 5.5: User1 - Check status (optional)
    - ``` git status ```
      This should show that there is no other files to commit and the working branch is clean
  - Step 5.6: User1 - Check log
    - ``` git log ```
    - This should show the log for 'add' and 'commit' with unique log id
  - [![alt_text](user1_add_commit_model.png)
- Step 5_2: User1 - Push local branch to remote repo
  - Step a: git push
- Step 5_a: User 2 - Git pull from user1_branch
- Step 5_b: User 2 - Change batch size in model.py
- Step 5_c: User 2 - Push local change to remote branch
- Step 6: User 1 - Pull from local branch
- Step 7: User 1 - Resolve conflict 
Step 4: Push Changes to Remote Repository
