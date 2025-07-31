# How2CreateOrDeleteRepositories
How to Create and/or Delete Repositories in github

#######################################################################

Step 1: Create a local git repository (see https://kamileyagci.github.io/GitHubRepo_from_Local/)



1.-  On terminal, go into your local project directory which you plan to create a git repository from.

        cd project_test

        Note: Use your own the directory path.

2.- Initialize the local git repository.

        git init

3.- (Optional) Create ‘.gitignore’ in your project directory. This file contains the list of files and directories to be excluded, not tracked and not uploaded, in the git repository. Even though it is not a required component, I highly encourage you to create one. See ‘More Tips’ section below to learn how to create .gitignore file.

4.- Add files to the repository.

        git add *

5.- Commit changes.
        git commit -am ‘Initial commit’


Spet 2 - Create a new blank repository on GitHub
(https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories)

1.- In the upper-right corner of any page, select +, then click New repository.

2.- Type a short, memorable name for your repository. For example, "hello-world".

3.- Optionally, add a description.

4.- Select Initialize this repository with a README.

5.- Click Create repository.

6.- Once the repository is created click the "<> Code" button and copy the 
    information under the ssh tab. Use this information to clone this 
    repository into your client.
    
#######################################################################

Also check: https://kamileyagci.github.io/GitHubRepo_from_Local/

Deleting a repository

(https://docs.github.com/en/repositories/creating-and-managing-repositories/deleting-a-repository)

1.- On GitHub.com, navigate to the main page of the repository.

2.- Under your repository name, click Settings tab 

3.- On the "General" settings page (which is selected by default), 
    scroll down to the "Danger Zone" section and click Delete 
    this repository.
