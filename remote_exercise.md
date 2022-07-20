## Instructions  
1. Create a repository on Github (without readme).  
    * create new repository  
2. In the terminal, initialize a new repository ..make a file and add and commit (Because without commit you dont have branch).  
    * mkdir  [file_name] ; git init [file_name]
    * git add . && git commit -m "commit message"
3. Add your remote repository to the local repository that you just created.  
    * git remote add origin <#url of repository on GitHub>
4. Check the repository's remotes.  
    * git remote -v (_verify that everything was successful in the above command_)
5. Create a branch on the repository and switch to it.  
    * git checkout -b [branch_name]
6. Add a readme file to the branch that you just created and add some text to the file.  
    * touch readme.md ; git add .; git commit -m "commit message"
7. Push the branch  
    * git push