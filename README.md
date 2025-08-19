

1st Pratical 

# 1. Initialize a new Git repository

```bash
 git init
```
    
# 2. Add a remote repository (replace with your actual GitHub repo URL)
```bash
 git remote add origin https://github.com/your-username/your-repo.git
```

# 3. Verify the remote URL
```bash
 git remote -v
```

# 4. Add all files to the staging area
```bash
 git add .
```

# 5. Check the status of the working directory
```bash
 git status
```

# 6. Commit the staged changes with a message
```bash
 git commit -m "I have made some changes in demo.txt"
```

# 7. Push changes to the main branch of the remote repository
```bash
 git push origin main
```

Practical  2
Commands
  git clone https://github.com/PhapaleSai/College_repo.git
    ls
   cd College_repo/
     ls
     vim sai.txt
     git status
     git commit -m "Added some content to sai.txt"
     git branch feature
     git checkout feature
     git remote add origin  https://github.com/PhapaleSai/College_repo.git
     git remote -v
     git push origin feature
     ls
     git add sai.txt
     git commit -m "sai.txt"
     git push origin feature
     git checkout main
     ls
     git pull origin main





