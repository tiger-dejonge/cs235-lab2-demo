# CS235 lab 2

in this lab, we first started with committing our git on terminal with our names and emails.

## Generating and linking out SSH keys with Github
We then made SSH keys and linked them up with our Github accounts which after watching the video was fairly easy. This is by first generating a new ssh key,  and then adding the key to a ssh agent. 

The next steps were going into out Github account and linking the ssh key with the account. 

## Repositories

our next task was making a new repository and pushing it into our Github account.

To start this, we go into our Github home page and create the repository, then we go into PyCharm and create a new project.

after this we had to make a .gitignore file and copy and paste the provided code. we then made a readme.md file.

We then intialised git on our terminal then added all the projects to git with the provided command. Then we added a message to the project and then got access to our git account with the command. Finally, we pushed all projects and files into our Github with the SSH key we generated earlier.

## Updating our repositories

After we pushed our files onto Github, we learnt how to update the files after we make modifications. 

## Hands on activities

We then began our more practical part of the lab and required us to work with a partner to complete the activities.

Luckily, part 0 was done earlier in our lab, we started on part 1. I started off by committing the project to the repository and then committing a requrements.txt file, then finished by adding student B as a collaborator. He then cloned the reposotory to his local machine and committed a .gitignore file. 

We then both created a branch and I implemented the 'get_rand()' function while he implemented the 'toss_coin()' function. 

We now then committed our codes and merged it to main and worked out our confilcts.

## Question 1

The best way to work on code from home in this scenario, would be to fork the repo of the main project and essentially have a new repo they can then request to pull to the original repo. 

## Question 2

Some of the differences between fork and merge is that with forking, it doesnt require you to be a collaborator and instead allow the user to make copy the repo into their own. They can then request to pull the repo which will then get the code accepted if acceptable.

Merge on the other hand, requires parties to be collaborators and allows collaborators to make branches of code or parts of code that needs amending. Once done, the branches can then be merged back with the main branch. This however can cause problems as if two coders are trying to merge the same section of code, then there is the potential of having conflicts which will then need sorting out.