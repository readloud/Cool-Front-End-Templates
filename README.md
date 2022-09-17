# Cool Front-End Templates

### This project is part of Girl script Summer of code 2022

## 💻 Tech Stack

### Front-End:

<img alt="HTML5" src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white"/> <img alt="CSS3" src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white"/> <img alt="JavaScript" src="https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>
<img alt="BootStrap" src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white"/>

## 🚀 Quick Start :

### Before starting kindly please read the [Code of Conduct](/CODE_OF_CONDUCT.md)

#### Step 1: Forking the repository :

To work on an open-source project, you will first need to make your copy of the repository. To do this, you should fork the repository and then clone it so that you have a local working copy.

Get your own Fork/Copy of repository by clicking `Fork` button right upper corner.<br><br>

#### Step 2: Clone the Forked Repository

After the repository is forked, you can now clone it so that you have a local working copy of the codebase.

To make your local copy of the repository follow the steps:

- Open the Command Prompt
- Type this command:

```bash
$ git clone https://github.com/<your-github-username>/Cool-Front-End-Templates
```

#### Step 3: Creating a new branch (IMP)

This is one of the very important step that you should follow to contribute to Open Source. A branch helps to manage the workflow, isolate your code and does not create a mess. To create a new branch:

```bash
$ git branch <name_of_branch>
$ git checkout -b <name_of_branch>
```

Keep your cloned repo up-to date by pulling from upstream (this will also avoid any merge conflicts while committing new changes)

```bash
git pull origin main
```

#### Step 5: Contribute

Make relevant changes according to the issue that you were assigned on. Contribute in any way you feel like :)

#### Step 6: Committing and Pushing

Once you have modified an existing file or added a new file to the project, you can add it to your local repository, which we can do with the git add command.

```bash
git add .
```

With our file staged, we’ll want to record the changes that we made to the repository with the git commit command.

The commit message is an important aspect of your code contribution; it helps the other contributors fully understand the change you have made, why you made it, and how significant it is.

```bash
git commit -m "useful commit message"
```

At this point you can use the git push command to push the changes to the current branch of your forked repository:

```bash
git push origin <branch-name>
```

#### Step 7: Create Pull Request

Now, you are ready to make a pull request to the original repository.

You should navigate to your forked repository, and press the "Compare & pull request" button on the page.

GitHub will alert you that you can merge the two branches because there is no competing code. You should add in a title, a comment, and then press the “Create pull request” button.

## CONTRIBUTING A NEW TEMPLATE?
### Please adhere to these guidelines 

1. Create a folder with the name of your frontend template 

2. Start building inside your folder with an entry file called index.html and after building, attach an image named "preview.png" within the folder root which represents the preview image of your template

3. Go into the style_link.json file and add an object corresponding to your project in the following format:
```
    {
  
      "name": "Name-of-folder-in-exact-case-used-in-naming",
      "link": "Name-of-folder-in-exact-case-used-in-naming/index.html"
  
    },

```
#### Important to note:  
If the folder name has white spaces e.g "My  Project", the object should be:

```
    {
  
      "name": "My Project", (not "my project" or "My project" or "My-project")
      "link": "My%20Project/index.html" (not "My Project/index.html" or "My project/index.html"
  
    },

```
#### Note: The name key is case sensitive and the link key is white space sensitive in the json object so if you have white spaces in the initial name of your folder, replace space with "%20" in the json link but if there are no white spaces like in the case of "ABlogPage" or "Form", use the exact name of the project

If the folder name has no white spaces e.g "My-project", the object should be:

```
    {
  
      "name": "My-project",  (not "my-project" or "My-Project" or "My Project")
      "link": "My-project/index.html"  (not "My%20project/index.html" or "My-Project/index.html")
  
    },

```
 
## ✨ Contributors

Thanks go to these **Wonderful People** 👨🏻‍💻: 🚀 **Contributions** of any kind are welcome!

## Happy Coding 👨‍💻

## 💬Join Our CodeSmashers Community

Join - https://discord.gg/gtYUZQSjTt

Show some ❤️&nbsp; by giving the star to this repo
