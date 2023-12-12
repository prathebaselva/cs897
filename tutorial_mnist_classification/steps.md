- Step 1: Set Up the Project
  - User1 : Create bare remote repository
  - ![alt text](bare_remote_repo.png)
- Step 2: Open terminal and cd to location to clone the remote github repository
- Step 3: Clone to local machine
  - User1 and User2: Clone repo to local machine
  ```git clone https://github.com/<username>/mnist_classification.git```
  - ![alt text](clone.png)
  - ![alt text](clone.mp3)
- Step 4: Create branches
  - User 1 : create branch1 from remote repo
    ```git checkout -b user1-branch```
  - User 2 : create branch2 from remote repo
    ```git checkout -b user1-branch```
  - ![alt text](branch.png)
- Step 5_1: User1 - Create model file and commit to branch
  - Step a: vi model.py
- Step 5_2: User1 - Push local branch to remote repo
  - Step a: git push
- Step 5_a: User 2 - Git pull from user1_branch
- Step 5_b: User 2 - Change batch size in model.py
- Step 5_c: User 2 - Push local change to remote branch
- Step 6: User 1 - Pull from local branch
- Step 7: User 1 - Resolve conflict 
Step 4: Push Changes to Remote Repository
