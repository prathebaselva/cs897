1. **Switch to the Desired Local Branch:**
 - Use the following command to switch to the branch where you want to make changes:
   ```bash
   git checkout <local_branch_name>
 - Example:
   ```bash
   git checkout feature-branch

2. **Make Changes to Your Code:**

3. **Commit your code:**
  ```bash
  git add .
  git commit -m "Add descriptive commit message"

4. **Push Changes to Remote Branch:**
  ```bash
  git push <remote_name> <local_branch_name>:<remote_branch_name>
 - Example
  ```bash
  git push origin feature-branch:feature-branch
 - Enter Credentials (if required):

5. **Check your remote repository on the hosting platform to ensure your changes are reflected in the remote branch.**
