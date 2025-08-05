# How2CreateOrDeleteRepositories
How to Create and/or Delete Repositories in github
(also see https://kamileyagci.github.io/GitHubRepo_from_Local/)

#######################################################################
- Create a new blank repository on GitHub
(https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories)

1.- In the upper-right corner of any page, select +, then click New repository.

2.- Type a short, memorable name for your repository. For example, "hello-world".

3.- Optionally, add a description.

4.- Select Initialize this repository with a README.

5.- Click Create repository.

6.- Once the repository is created click the "<> Code" button and copy the 
    information under the ssh tab. Use this information to clone this 
    repository into your client.
        see example below.
        
        #git init
        #git add README.md
        #git commit -m "first commit"
        #git branch -M main
        #git remote add origin git@github.com:llueveYescampa/OpenStruc.git
        #git push -u origin main
    
    
#######################################################################

Also check: https://kamileyagci.github.io/GitHubRepo_from_Local/

Deleting a repository

(https://docs.github.com/en/repositories/creating-and-managing-repositories/deleting-a-repository)

1.- On GitHub.com, navigate to the main page of the repository.

2.- Under your repository name, click Settings tab 

3.- On the "General" settings page (which is selected by default), 
    scroll down to the "Danger Zone" section and click Delete 
    this repository.
