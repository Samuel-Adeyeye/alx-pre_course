# Exploring Git Command Line & GitHub Functionalities

The following information have been provided to guide the reader on how to setup a git repository and create changes using git command line.
Acknowledgement: Kindly note that I have adapted these guidelines from an "Introduction to Git" tutorial from the ALX Software Engineering Programme.

### Basic usage
At the end of this project you should be able to reproduce and understand these command lines:
* $ git clone <repo>
* $ touch test
* $ git add test
* $ git commit -m "Initial commit"
* $ git push origin main
  

# Create and setup your Git and GitHub account
### Step 1 - Create an account on GitHub [if you do not have one already]
  You will need a GitHub account for all your projects as a software engineer. If you do not already have a github.com account, you can create an account for free [here](https://github.com/login)
### Step 2 - Create a Personal Access Token on Github
  To have access to your repositories and authenticate yourself, you need to create a Personal Access Token on Github.
  You can follow this [tutorial](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) to create a token.
  
### Step 3 - Create your first repository
Using the graphic interface on the github website, create your first repository.
### Step 4 - Clone your repository
  * $ git clone https://{YOUR_PERSONAL_TOKEN}@github.com/{YOUR_USERNAME}/alx-pre_course.git

Name: alx-pre_course
Description: I'm now a ALX Student, this is my first repository as a full-stack engineer
Public repo
No README, .gitignore, or license

Replace {YOUR_PERSONAL_TOKEN} with your token from step 1
Replace {YOUR_USERNAME} with your username from step 1 and 2
Pro-Tip: On windows, use CTRL + A + V to paste in the web terminal
  
### Step 5 - Create the README.md and push the modifications
  * Navigate to this new directory. [Tips](https://askubuntu.com/questions/232442/how-do-i-navigate-between-directories-in-terminal)
  * $ cd alx-pre_course/
  * $ alx-pre_course#
  
  * Create the file "README.md" with the content "My first readme". [Tips](https://forum.howtoforge.com/threads/echo-into-a-file.115/)
  * $ alx-pre_course# echo 'My first readme' > README.md                                                                 
  * $ alx-pre_course# cat README.md                                                                                      
  
  * Update your git identity
  * $ alx-pre_course# git config --global user.email "you@example.com"
  * $ alx-pre_course# git config --global user.name "Your Name"
  
  * Add this new file to git, commit the change with this message “My first commit” and push to the remote server / origin
  * $ alx-pre_course# git add .
  * $ alx-pre_course# git commit -m 'My first commit'
      [master (root-commit) 98eef93] My first commit
      1 file changed, 1 insertion(+)
      create mode 100644 README.md
  * $ alx-pre_course# git push                                                                                           
      Enumerating objects: 3, done.                                                                                                         
      Counting objects: 100% (3/3), done.                                                                                                   
      Writing objects: 100% (3/3), 212 bytes | 212.00 KiB/s, done.                                                                          
      Total 3 (delta 0), reused 0 (delta 0)                                                                                                 
      To https://github.com/{YOUR_USERNAME}/alx-pre_course.git                                                                                       
      * [new branch]      master -> master   
  
Good job!
You pushed your first file in your first repository of the first task of your first ALX School project.
You can now check your repository on GitHub to see if everything is good.
  
