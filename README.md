# How to make a repository and upload it to Github from scratch.

## Step 1: Create a folder locally.
- On your computer, create a folder where you will store your project files. We will call the file Folder A.
- Save all your files in Folder A

## Step 2: Open your terminal.
- Open command prompt or your terminal application.
- Navigate to the folder you just created using the `cd` command:
    ``
    cd "C:\path\to\Folder A"
    ``

## Step 3: Initialize Git and stage your files.
- Turn your folder into a Git respository by running `git init`.
- Add all the files in the folder to Git's "staging area" using `git add .`.

## Step 4: Commit your changes.
- Save your changes locally by creating a commit using `git commit -m "Initial commit"`
    
The `-m` allows you to add a message for the commit.

## Step 5: Create a repository on Github.
- Login to Github
- Click the green button on your Github dashboard.
- Fill out the repository details.
- It is important to leave the checkbox for "Initialize this repository with a README" unchecked.
- Click "Create repository".
- Copy the repository URL.

## Step 6: Link your local repository to Github.
- Go back to the terminal, link your local repository to the remote Github repository by running:
    ``
    git remote add origin git@github.com:username/MyProject.git
    ``
Replace username with your Github username and MyProject with repository name.

## Step 7: Push your files to the Github.
- Push your files to the Github repository using `git push -u origin main`.

## Step 8: Verify on Github.
- Refresh your Github repository page.
- You should see all your files uploaded.    
