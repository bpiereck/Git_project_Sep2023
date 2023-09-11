# Manual of git commands

1. How to initialize git
   
   `git init`

2. How to send to the staging area
   
   `git add <file_name>`
   
   - **How to use it cleverly:**
     use git status to check before you commit
     `git add <file 1> <file 2> `
     `git commit -m "msg that express something both files have in common"`

3. How to commit a change to creat my 1st snapshot 
   
   `git commit -m "MEANINFUL MESSSAGE"`
   
   P.s.: Meaninful msg: Why, How, Limitations, Effects

4. How to check in what conceptual areas my files are
   
   `git status`

        P.s.: Uncommited, Unstaged, Untracked files

5. Hot to get the history:
   
   `git log `
   
   `git log -n <no>`
   
   `git log --abbrev-commit`
   
   `git log ---help`

6. How to compare versions of the same file:

        `git diff <commit ID> <commit ID>`

        `git show <commit ID> <commit ID>`

       ` git show -2 <file name>` (to check the last 2 versions of a file)

7. How to create and use a link between local and remote repository
   
   - Create a link ('bridge')
     
     `git remote add <name4link> <ssh>`
     
     **obs.:** name4 link is usually the same name as my repositories, but can be anything I like. It is just a name for the link that is being created.
   
   - Send things from local to your remote repository
     
     `git push`


