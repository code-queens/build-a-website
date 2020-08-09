# Learn to code a website from scratch!
Welcome to +1 Code Queens! This repository will get you started on the path to building your very own website. Even though we are all starting from the same place, by the end of the class you will have your own unique project to show off. So let's get started!

## Start a project folder
Make a new folder anywhere on your computer and name it CodeQueens. Remember where you put it, as this will be where you store your code for the class and how you see what you create!

## Set up your GitHub account
GitHub is an industry leading platform that allows coders from all over the world collaborate on projects. We'll be using it to create a repository for our code, which you can think of as a project folder. GitHub allows you to make changes to your code and save them to your repository, while also tracking the history of your changes. That way, if you make a mistake or want to go back to a previous version of your project, you can do that using GitHub.

Go to github.com to set up your free account. You'll need to pick a username for yourself, enter in an email address, and set a password. 

GitHub will then send you a confirmation email in which you can verify your account. 

Once your account is verified, login to GitHub and start checking it out!

## Find the code-queens project
In the search bar in the upper left hand corner in GitHub, search code-queens/build-a-website. This will open up the repository for our project. You should see this document on the screen below the project directory.

## Fork the project
In the upper right hand corner, click the button that says Fork. This will make a copy of the code-queens project in your personal GitHub account. You will then be able to build off the code and make this project your own!

## Add the project to Visual Studio Code
We will be using Visual Studio Code (aka VS Code) to write our code. VS Code is an integrated development environment (most people just say IDE for short), which is a fancy way of saying an application to write code. There are a lot out there, but VS Code is very popular and well supported and maintained (it's owned by Microsoft!). Even though our project is starting from GitHub, we will use VS Code to develop on our local machines, then save our changes back to GitHub when we're ready.

To add the project to VS Code, go to your copy of the project on GitHub. It should be called [YOUR USERNAME]/build-a-website. 

From the main page of this repository, find the green button that says Code. When you click on this button, a modal should pop up with a link to the repository. 

Click on the clipboard icon to the right of this link to copy it.

Now go to VS Code and open a new window. 

In the menu on the left hand side, click on the third icon from the top (not sure how to describe this image...looks like circuitry to me). This is the source control button. 

In the panel that opens up, click Clone Repository. 

You should now be directed to paste the link that you copied in the search bar at the top of the screen. Press enter when done. 

A modal will pop up asking where you want to store the files for the project. This is where your CodeQueens folder comes in! Find this folder, select it, then click Select Repository Location. 

Once it loads, click on the Open button when prompted in the bottom right hand corner.

Now you should see a copy of all the files from the project in VS Code!

## Let's see it in action!
Navigate to your CodeQueens folder on your computer (not in VS Code) and find the index.html file there. 

Double click on the file to open it in your browser. 

Now you should be able to see the beginnings of your very first website!

## Making your first commit
Follow the instructions on the screen to make some updates to the HTML code. Once you are satisfied with your changes, you can commit them to your GitHub repository. Think of this as saving your changes, but instead of saving them only on your computer, you will also save them to GitHub. 

First, let's check to see what files were changed. In the VS Code Terminal, type the following command:
```
git status
```

This will show you a list of any added, removed, or modified files since your last commit. You should see the index.html file on the list that you recently modified. Let's mark this file as one we want to save. To do so, run the following command in your terminal:
```
git add index.html
```

This command adds the index.html file to the set of files that we want to save in our commit. Now we're ready to execute our commit:
```
git commit -m "type a message here that describes the changes you made"
```

The command we just ran looks a bit different from the previous ones. The "-m" after commit is what we call a flag. It signals that we want to add an argument to the command and that the argument is a message. That is what the text in quotations is. You can make your message say whatever you want, but it is helpful to write here a short description about what you changed in your code that will be saved with this commit.

We have one final step before our changes are saved to GitHub. We need to push our commit. What that means is that we are taking the changes saved in our commit on our local environments (your computer) and sending it to the GitHub website so that it can save a copy there. To do so, execute the following command:
```
git push
```

You did it! You have successfully made your first commit to GitHub. Congratulations!

## Resources
- Git Guide: https://guides.github.com/introduction/git-handbook/
- Stack Overflow: https://stackoverflow.com/
- HTML Reference: https://www.w3schools.com/html/html_intro.asp
- CSS Reference: https://www.w3schools.com/cssref/default.asp
- Google Fonts: https://fonts.google.com/