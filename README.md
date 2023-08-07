# git-basic-staging


### 1. What's the content of file.txt?
<img src="/staging/staging1.png">


### 2. Overwrite the content in file.txt: echo 2 > file.txt to change the state of your file in the working directory (or sc file.txt '2' in PowerShell)
<img src="/staging/staging2.png">


### 3. What does git diff tell you?
<img src="/staging/staging3.png">
<p> 1 has been deleted and 2 is added </p>

### 4. What does git diff --staged tell you? why is this blank?
<img src="/staging/staging4.png">
<p>it should be blank because i didnt add the the file to the staging area, so all the changes will not be tracked.</p>

### 5. Run git add file.txt to stage your changes from the working directory.
<img src="/staging/staging5.png">


### 6. What does git diff tell you?
<img src="/staging/staging6.png">


### 7. What does git diff --staged tell you?
<img src="/staging/staging7.png">


### 8. Overwrite the content in file.txt: echo 3 > file.txt to change the state of your file in the working directory (or sc file.txt '3' in PowerShell).
<img src="/staging/staging8.png">


### 9. What does git diff tell you?
<img src="/staging/staging9.png">


### 10. What does git diff --staged tell you?
<img src="/staging/staging10.png">


### 11. Explain what is happening
<p> before adding file.txt to the staging area no changes were tarcked, but when i added file.txt to the staging area all changes were saved andare ready to be commited to my own cloned repo </p>

### 12. Run git status and observe that file.txt are present twice in the output.
<img src="/staging/staging12.png">
<p> the first one is the copy after being added to the staging area, the second one is the one before adding it to the staging area. </p>

### 13. Run git restore --staged file.txt to unstage the change
<img src="/staging/staging13.png">


### 14. What does git status tell you now?
<img src="/staging/staging14.png">
<p> the staged changes were removed. </p>

### 15. Stage the change and make a commit
<img src="/staging/staging15.png">


### 16. What does the log look like?
<img src="/staging/staging16.png">
<p> it says that there is one changed file with one line inserted and one line deleted. </p>

### 17. Overwrite the content in file.txt: echo 4 > file.txt (or sc file.txt '4' in PowerShell)
<img src="/staging/staging17.png">


### 18. What is the content of file.txt?
<img src="/staging/stagin18.png">


### 19. What does git status tell us?
<img src="/staging/staging19.png">


### 20. Run git restore file.txt
<img src="/staging/staging20.png">


### 21. What is the content of file.txt?
<img src="/staging/staging21.png">


### 22. What does git status tell us?
<img src="/staging/staging22.png">
<p> the last commited change was restored and the last unstaged change is removed, there are no changes to be staged or commited. </p>

