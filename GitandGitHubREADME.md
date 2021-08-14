# DevOps
## Practice Session 1 : Getting started with Git and GitHub Commands

In this session, you will learning cloning an existing repository, creating a branch, making changes, and creating a pull request. Along the way, you might also learn how to find your terminal, use terminal commands, and edit a markdown (.md) file!

## Let’s get started!

## What is Git? What’s GitHub?
Git is the version control tech of choice for basically everybody right now, from developers to designers. 
GitHub is the social code-hosting platform that’s currently used more than any other. 
* It’s a place where you can play and experiment. 
* It’s a place where you can find (and play around with) the most incredible open-source information, emerging technologies, features, and designs. 
* It’s a place to learn and it’s a place to get involved. 
* You can keep code there for work or for school, and you can grab some sweet code that you want to explore further. 
* You can even host websites for free directly from your repository!

Any time you see a command in this article that includes these marks: < > , you want to delete those marks and replace what’s between them with your own information. Let’s say you see something like git add <filename>. That means that you would type, for example, git add hello_world.py 

## Step 1: Sign up and installation!

Go to GitHub and sign up for an account. To install Git if you haven’t already. If you want to work on your local computer, then you want to have Git installed. 
To set your username for every repository on your computer, type

  * git config --global user.name "<your_name_here>"

replacing “<your name here>” with your own name in quotations. If you want to set your name for just one repository, leave out the word “global.”
Now you can provide Git your email, and make sure it’s the same email you used when you signed up for GitHub

  * git config --global user.email "<your_email@email.com>"

If you have a project directory, just go to your terminal and in your project directory run the command

  * git init 

If you want to initialize your project with all of the files in your project directory, run

  * git init .

to include everything.

Let’s say you have a folder  called “my_project.” You could switch to that folder and add a local repository to it by running

  * cd my_project
  * git init
  * ls -la 

you observe a new hidden directory called .git in your project directory. This is where Git stores the files that it can track your project. 

Create one or two new files such as  <file1.txt> and <file2.txt>  in the same folder.  Add the files to the staging area one by one with

  * git add <filename_one>

or run

  * git add .

to add all of your files to the staging area. You can commit these changes with the command
  * git commit -m "<add a commit message here>"

and if you’re happy with your changes, you can run

  * git push

to push your changes through to Git Hub repository. Check the status by running

  * git status

If you made some changes, you can update your files on at a time with

  * git add <filename>

or

  * git add --all

Then commit them with your commit message and push them through.That’s it! You can now initialize a repository, commit files, commit changes, and push them through to the master branch.

## Option2:

If you  want to create a new repository. Your repository is where you’ll organize your project. You can keep folders, files, images, videos, spreadsheets, Jupyter notebooks, 
data sets, and anything else your project needs. 
Before you can work with Git, you have to initialize a repository for your project and set it up so that Git will manage it. You can do this right on the GitHub website.
It’s a smart idea to include a README file with information about your project. You can create one at the same time that you create your repository with the click of a checkbox.

* Go to the GitHub website, look in the upper right corner, and click the + sign and then click “New repository.”
* Name the repository, and add a quick description.
* Decide whether you want this to be a public or a private repository
* Click “Initialize this repository with a README” if you want to include the README file. (this is a recommended process. It’s the first thing people are going to look at when they check out your repository. 
It’s also a great place to put information that you need to have in order to understand or run the project.)

You can now upload files, edit files, and so on right from your repository on the GitHub website. 
There are two ways to make changes to your project. 
* You can make changes in your files/notebooks on your computer 
* you can also make changes right on GitHub.

Let’s say you want to make some changes to your README file right on GitHub.

* First, go to your repository.
* Click the name of the file to bring up that file (for example, click “README.md” to go to the readme file).
* Click the pencil icon in the upper right corner of the file and make some changes.
* Now the changes have been made to the README file in your new repository! 

## Option3:

Some people prefer to work with files on their  local computer rather than try to make everything work from the GitHub website. 
You might want to clone your new repository so that you can work on it on your local computer,or you might have an existing repository that you want to clone. 
(That’s something you might need to do that for a project or course.)
* In order to clone a repository onto your computer, go to the repository on the GitHub website and click the big green button that says “Clone or download.” 
(You can definitely download the repository right there and skip the terminal stuff if you just can’t deal with it.) Make sure it says “Clone with HTTPS.” 
Now click the clipboard icon to copy and paste it to your clipboard (or highlight that link and copy it).
* Write a short message in the box that describes the changes you made (and an extended description if you want).
* Click the “Commit changes” button.

Now open the folder in your terminal  place where you want that repository to be copied. For instance, type

  * cd my_folder 

To clone the repository, you type

  * git clone <that_thing_you_just_copied>

Now you have a new GitHub repository that you can work with cloned right on your desktop! 

## Option 4:

you can fork the repository or files on the GitHub website instead of cloning it. Look up near the top right corner of the screen for the “fork” button
and click it. This will make a copy of the repository in your repositories for you to work with without making any changes to the original copy.
Now it’s time to add some files to your project!

* git status
* git add
* git commit -m " "
* git push

Go to your terminal project folder. Then run

  * git status
to see if everything is up to date. 

To add one of your files to the repository, you would run
  * git add <fileneame>
Otherwise, you can add everything with
  * git add –all

or even
  * git add .

You aren’t actually adding anything just yet. You’re bringing new files and changes to Git’s attention.
To commit the changes, you will start the process by running

  * git commit -m “<commit message>”

You’re committing the changes to the HEAD, but not to the remote repository. (Make sure you replace that message in quotes with your own.) When you make a commit, 
file is saved and includes a message about what you changed and/or why you changed it. Now the changes are in the head location of your local working copy. 
To send the changes to your remote repository, run

  * git push

to push your changes right into your repository. If you’re working on your local computer and you want your commits to be visible online too, you would push the 
changes up to git hub with the git push command. You can see if everything is up to date any time by running the git status command!
### So now you have a GitHub repository and you know how to add files and changes to it!
### Congratulations !!


