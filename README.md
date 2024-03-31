# New Project Setup Guide
Welcome to the setup guide for the **`new-project`** repository. This document will walk you through the process of creating a new Git repository, setting up a development branch, and merging changes back to the main branch.

## Prerequisites
- Git installed on your machine. [Download Git](https://git-scm.com/downloads)
- A GitHub account. [Sign up for GitHub](https://github.com/join)

## Step 1: Create a New Repository on GitHub

1. Sign in to your GitHub account.
2. Navigate to the Repositories tab.
3. Click the **`New`** button.
4. Enter **`new-project`** as the repository name.
5. Choose the visibility for your repository (Public or Private).
6. Click **`Create repository`**.

## Step 2: Clone the Repository
Open a terminal or command prompt and run the following command, replacing **`YOUR_USERNAME`** with your GitHub username:

```bash
git clone https://github.com/YOUR_USERNAME/new-project.git
cd new-project
```

## Step 3: Create a Development Branch
Create a new branch named **`development`**:

```bash
git checkout -b development
```

## Step 4: Add a README.md File
1. Create a **`README.md`** file in the root of your project directory.
2. Open the **`README.md`** file with a text editor and add your project information.
3. Save your changes.

## Step 5: Commit Changes to the Development Branch
Commit your changes with a meaningful message:

```bash
git add README.md
git commit -m "Add initial README.md"
```

## Step 6: Push Changes to GitHub
Push your changes to the **`development`** branch on GitHub:

```bash
git push -u origin development
```

## Step 7: Merge Development Branch into Main

1. Switch to the **`main`** branch:
```bash
git checkout main
```
2. Merge the **`development`** branch into the **`main`** branch:

```bash
git merge development
```
3. Push the changes to GitHub:
```bash
git push origin main
```

## Conclusion
Congratulations! You have successfully set up a new Git repository for **`new-project`**, created a development branch, and merged changes into the main branch. You're now ready to continue working on your project.