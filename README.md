Task:
**1) Git commands**
**2) Readme Commands(fonts)**
**3) links to various txt files**
**4) create a folder in repo and save a txt filr and link it to the main repo README**


# GIT Commands

## Author :- Who Developed File
## Commit :- Who do some changes in file


___ ___

    git init

This command is use to initialise git in your local directory.

    git status
    
This command is use to check the status of Present Working Directory.

    git add --a 
    
This command is use to make file ready to commit.

    git commit -m "#Comment" 

This command is use to commit the file.

    git rm -rf .git
    
This command is use to delete the git from your local directory

    git push 
    
This command is use to push the data on  host server.

    git pull 

This command is use for taking data from out source.
    
    git clone (url)
    
This command is use for taking data from any repository to your local device.

    git diff

This command compare staging area to working directory.(check what is different data between staging file and after staged file which file we have modified.)

    git diff --staged
    
This command compare previous commit and current stagging area (shows what changes had happened.)

    git commit -a -m "comment" 

This command use for direct commit. if you have done changes in file,which is allreary in staging area.(This command skip the stagging area)

    git  log -p
    
This command shows log with diff(show what things are changened in the files.)

    git log --p -3
    
Only shows info of 3 comments

       git log --stat
       
give short info of commit.

    git log --pretty=oneline
    
give commit info in one line

    git log --pretty=short
    
give commit info in very short.

    git log --pretty=full
    
give more info about commit:

    git --since=2.days
    
show only info which commited in last 2 days.

    git --since=2.months

show only infro of two months.

    git --since=2.years
    
show for only two years.

      git log --pretty=format:"%h -- %an"

    


## .gitignore: Ignoring Files in Git.

    
