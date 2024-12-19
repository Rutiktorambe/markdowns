## Git Commands Documentation

### Setting Up Git Account

1. Configure your Git account:

   ```bash
   git config --global user.name "Name"
   git config --global user.email "email"
   ```

2. Verify the configuration:
   ```bash
   git config --list
   ```

### Common Git Commands

#### 1. Create a New Repository

- Initialize a new Git repository:

  ```bash
  git init
  ```

- Add a remote repository:

  ```bash
  git remote add origin <repository_url>
  ```

#### 2. Create a New Branch

- Create and switch to a new branch:

  ```bash
  git checkout -b <branch_name>
  ```

#### 3. Switch to an Existing Branch

- List all branches:

  ```bash
  git branch
  ```

- Switch to an existing branch:

  ```bash
  git checkout <branch_name>
  ```

#### 4. Add and Commit Changes

- Add all changed files:

  ```bash
  git add .
  ```

- Commit the changes:

  ```bash
  git commit -m "Commit message"
  ```

#### 5. Push Changes to Remote Repository

- Push changes to the current branch:

  ```bash
  git push origin <branch_name>
  ```

#### 6. Pull Changes from Remote Repository

- Pull the latest changes:

  ```bash
  git pull origin <branch_name>
  ```

#### 7. Fetch and Merge Changes

- Fetch updates from the remote repository:

  ```bash
  git fetch origin
  ```

- Merge the changes into your branch:

  ```bash
  git merge origin/<branch_name>
  ```

---
