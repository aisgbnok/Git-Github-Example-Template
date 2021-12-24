# Git & GitHub Example

This repository is used as an example space for understanding Git & GitHub. Feel free to duplicate
this repo and mess around.

## Authors

- Anthony Swierkosz (aisgbnok)
- <name> (<GitHub username>)

## Exercise

Let's do a few simple exercises to provide a basic understanding of Git & GitHub.

### 0. Copy this Repository

#### Duplicate Template

This repository is a template repository, so first we need to make a copy on your GitHub account.

1. Click the `Use this template` button on the repo's GitHub homepage
   or [navigate to this link.](https://github.com/aisgbnok/Git-Github-Example-Template/generate)
    - This will duplicate the repo but keep all the files.
    - This repo is owned by `aisgbnok/Git-Github-Example-Template`
    - The new repo is owned by `<your GitHub username>/<repo name> `
2. Choose a `repository name` for this duplicate
3. You can ensure only you have access to the repo by making it private, or you can keep it public
   where anyone can see this on your GitHub profile.
4. Create the new repository from the template.

#### Cloning your Repository

> Remember 💡
>
> - Git is an open-source DVCS that runs locally on your computer.
> - GitHub, while sharing the Git name, is a proprietary hosting platform for Git repositories. GitHub itself is not a version control system.

We just generated a new repository on GitHub's remote server. To start working on this repository we
need to connect Git on your local machine to this repository on GitHub's server.

If we had this repository already on our machine we would manually set GitHub as a remote repository
and then sync (push & pull) changes. However, because we don't have this repository on our machine
we can clone it and Git will automatically configure everything we need (set the remote & sync
changes).

> The two main options for using/interfacing with Git are:
>
> - Using third-party Graphical User Interfaces (GUIs) like [GitHub Desktop](https://desktop.github.com/), an IDE with Git integration like [JetBrains IDEs](https://www.jetbrains.com/), or [GitKraken](https://www.gitkraken.com/).
> - Using the [Git command line / terminal commands.](https://git-scm.com/docs/git)
>
> The purpose of Git is to improve a developer's productivity. Many choose to learn Git terminal
> commands, but others only use Git through a GUI. IDEs like JetBrains have a phenomenal and robust
> Git GUI built right in.
>
> Therefore, I will always provide the Git terminal commands, and I will try to provide GUI
> instructions for JetBrains IDEs as well.

To clone the repository we need to copy the GitHub HTTPS URL and give it to Git. JetBrains has
a [great blog post on cloning](https://blog.jetbrains.com/idea/2020/10/clone-a-project-from-github/)
and [other Git documentation for their IDEs.](https://www.jetbrains.com/help/idea/set-up-a-git-repository.html)

1. Click the <kbd>**Code** ▼</kbd> dropdown button on your GitHub repository's homepage.
2. Copy the HTTPS URL, which will look like:

```
https://github.com/<Your Username>/<Repo Name>.git
```

> Continue below for terminal commands, or follow the JetBrains blog/documentation links above if using their IDE.

> You can choose to use both terminal or IDE GUI interchangeably. For example, you can clone this repository using terminal commands and then once you open the project in your IDE it will automatically detect the `.git` folder and enable Git support.

3. Open terminal on your machine
4. In terminal, navigate to the directory you plan on placing your repository
    - For example `C:\Users\Anthony\Documents\Projects>` on Windows
5. Clone the repository and give Git the GitHub HTTPS URL you copied in step 2

Command:

```
git clone <GitHub URL>
```

Example

```
C:\Users\Anthony\Documents\Projects> git clone <GitHub URL>
```

This will create a new directory with the name of your repo, initialize git, and pull all history
from the GitHub server.

Go ahead and open the directory on your machine or in your IDE, you should see the `.git` directory
and this `README.md` file.

### 1. Change your `README`

Let's start with something simple. This README.md is a markdown file. Markdown files are text files
with some basic formatting abilities. Markdown files have a `.md` file extension and are widely used
by developers for documentation. (Like having a README file explaining what their repository does.)

Let's clean up this repository now that it is yours!

1. Start by removing all of section `0. Copy this Repository` until you get to
   section `1. Change your README`

> Make a commit.

### 2. Add another Markdown File

Add another markdown file and make a commit.