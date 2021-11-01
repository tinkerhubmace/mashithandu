# MBCCET
![Campus Logo](https://user-images.githubusercontent.com/37255301/137591573-ee171112-7a97-45f4-bd74-750d04411526.png)

## Instructions for students

- #### If you don't have Git Bash on your machine, [install it](https://git-scm.com/downloads).
If you are new to Git and Github, you need to [create a Github Account](https://github.com). It is advisable that you go through [Git Handbook](https://guides.github.com/introduction/git-handbook/) before moving to next step.  


## Fork the repository  
<img align="right" width="300" src="https://user-images.githubusercontent.com/37255301/137591693-4f97ac88-adea-46df-90b9-fc84e4498723.jpg" />
Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.  

## Clone the repository  
Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the copy to clipboard icon.

Open Git Bash and run the following git command:

```
git clone url 
```

where url  is the url you just copied! (your fork of this project).
<img align="right" width="300" src="https://user-images.githubusercontent.com/37255301/137591725-e2ecbdae-1ece-4170-b2a8-97e8686d5e35.png" />  
For example:

```
git clone https://github.com/tinkerhubmbc/mashithandu.git
```

where `username` is your GitHub username. Here you're copying the contents of the mashithandu repository on GitHub to your computer.  
  
## Make necessary changes

Open up the project in your favourite text editor, select the file you want to contribute to, and make your changes.Make sure to save the edits.

All the files in this project are ```.md``` files. You would need to have Markdown knowledge to contribute to this project.  
  
  
Markdown is a fast and easy way to take notes, create content for a website, and produce print-ready documents. It doesn't take long to learn the Markdown syntax, and once you know how to use it, you can write using Markdown just about everywhere. Visit [here](https://guides.github.com/features/mastering-markdown/) to master Markdown.

## Add and Commit your changes
Open Git Bash, navigate to the project directory and execute the command ```git status```, you'll see there are changes.
 Add those changes to the branch you just created using the `git add` command:

```
git add filename.md
```
You can also add all the unstaged files using : ```git add .```  

Now commit those changes using the `git commit` command:
<img align="right" width="300" src="https://user-images.githubusercontent.com/37255301/137591744-a5b60efe-e739-42b6-8115-6161fc1f49d1.png" /> 

```
git commit -m "commit message"
```
       
## Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin main
```

## Create a pull request
  
<img align="right" width="300" src="https://user-images.githubusercontent.com/37255301/137591763-1ad6a459-8ce8-4bc2-aa02-af11e7b5a44a.png" /> 
Open the main page of your repository on your GitHub account in your browser and click on the Pull requests tab.  
Now, click on the New Pull Request button.  
Click Create Pull Request option. Enter a suitable title and description for the pull request. Now submit the pull request.    

  
What is a [pull request?](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)    
  
You can find more GitHub Commands [here](https://www.geeksforgeeks.org/list-useful-github-commands/)
  
__Congrats! You just completed the standard fork -> clone -> edit -> pull request workflow that you'll encounter often as a contributor!🎉__



## Contacts

The contact points students/TinkerHub can reach out to if needed

Lead Name - athulofficial01@gmail.com/+91 88483 38058
For support - ashiksaleem20@gmail.com/+91 85900 70941
