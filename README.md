# Important Git Commands

**git init** : Initializes a new git repository.

**git config --global user.name "Username"** : Sets the global username.

**git config --global user.email "Email"** : Sets the global email.

**git add** : 

 - **git add \.** \- Adds everything to the staging phase.
 - **git add \*.txt** - Adds all the files ending with .txt.
 - **git add file_name.ext** - Adds a particular file.

**git commit -m "Message..."** : Creates a local repository with all the changes.
 - **Ex** : ```git commit -m "Initial Commit"```

**git status** : Returns the status of the changes in the local repository

**git remote add remote-name "URL of the Repo"** - Creates a remote that you can use to connect to the online repository.
 - **Ex** : ``` git remote add github "https://github.com/packetcode/git-crash-course.git" ```

**git push remote-name branch-name** : Pushes or adds or transfers the files to the remote repository.
 - **Ex** : ```git push github master```
 - **Force Push** : ```git push -f github master```

**git clone "URL"** : Clones the repository into the local machine.
 - **Ex** : ```git clone "https://github.com/packetcode/git-crash-course.git"```
 - **git clone "URL" folder-name** : Clones the project into a specified folder without creating any other folder by default.
   - **Ex** : ```git clone "https://github.com/packetcode/git-crash-course.git" testing-project``` 

**git pull** : Adds any changes/updates made in the remote repository to the local repository.

**git branch branch-name** : Creates a branch.
 - **Ex** : ```git branch testing```

**git checkout branch-name** : Shifts the head to the specified branch i.e. changes the branch that we are currently working on.
 - **Ex** : ```git checkout testing```

**git merge branch-name** : Merges the code present in the specified branch to the main **master** branch.
 - **Ex** : ```git merge testing```

---

This repo was created to be used as a reference for [this](https://www.youtube.com/watch?v=IgX7tHe5onI) YouTube video explaining Git commands. But feel free to fork this repo if you want to use it as a **cheatsheet**.
