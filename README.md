# Git & GitHub Example

This repository is used as an example space for understanding Git & GitHub. Feel free to copy this
repository and mess around; however, please provide attribution.

## Authors

- Anthony Swierkosz (aisgbnok)
- <name> (<GitHub username>)

## Exercise

Let's do a few simple exercises to provide a basic understanding of Git & GitHub.

### 0. Generate New Repository

This repository is
a [template repository,](https://docs.github.com/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template)
that you can't modify because I own it. So to get started we need to generate a new repository, that
you own, based on this one. This is done on the GitHub website.

#### Generate New Repository

1. Click the <kbd>Use this template</kbd> button at the top of this repository's GitHub homepage
   or [navigate to this link.](https://github.com/aisgbnok/Git-Github-Example-Template/generate)
    - This will generate a new repository based on this template repository.
    - This repository is owned by me, `aisgbnok/Git-Github-Example-Template`
    - The new repository will be owned by you, `<your GitHub username>/<repo name> `
2. Choose a repository name, like `git-github-example`.
3. You can ensure only you have access to the repository by making it private, or you can keep it
   public allowing anyone to see this on your GitHub profile.
4. Create the new repository from this template.

### 0. Using your Repository

Remember, you don't have permission to edit the `aisgbnok/Git-Github-Example-Template` repository.
So from now on you must use your own repository. You just generated your own repository based on
the [`aisgbnok/Git-Github-Example-Template`](https://github.com/aisgbnok/Git-Github-Example-Template)
repository.

If you aren't already reading this on your own personal repository, this would be a good time to
close the `aisgbnok/Git-Github-Example-Template` repository, open your newly generated repository,
and continue the following steps there. 👍

### 1. Cloning this Repository

To start working on this repository we need to connect Git on your local machine to this repository
on GitHub's server.

> Remember 💡
>
> - Git is an open-source DVCS that runs locally on your computer.
> - GitHub, while sharing the Git name, is a proprietary hosting platform for Git repositories. GitHub itself is not a version control system.

Right now, this repository only exists on GitHub's server. We need to clone it locally using Git.
When we clone a repository Git will automatically configure everything we need (set GitHub as a
remote & pull this repository from the remotes).

> The two main options for interfacing with Git are:
>
> - Using third-party Graphical User Interfaces (GUIs) like [GitHub Desktop](https://desktop.github.com/) or IDEs with Git integration like [JetBrains IDEs.](https://www.jetbrains.com/)
> - Using the [Git terminal commands.](https://git-scm.com/docs/git)
>
> The purpose of Git is to improve a developer's productivity. Many choose to learn Git terminal
> commands, but others only use Git through a GUI. IDEs like JetBrains have a phenomenal and robust
> Git GUI built right in.
>
> Therefore, I will always provide the Git terminal commands, and I will try to provide GUI
> instructions for JetBrains IDEs as well.

#### Cloning

To clone this repository we need to copy the GitHub HTTPS URL and give it to Git. JetBrains has
a [great blog post on cloning](https://blog.jetbrains.com/idea/2020/10/clone-a-project-from-github/)
and [other Git documentation for their IDEs.](https://www.jetbrains.com/help/idea/set-up-a-git-repository.html)

1. Click the <kbd>**Code** ▼</kbd> dropdown button on your GitHub repository's homepage.
2. Copy the HTTPS URL, which will look like:

```
https://github.com/<Your Username>/<Repo Name>.git
```

> Continue below for terminal commands, or follow the JetBrains blog/documentation links above if using their IDE.

> You can choose to use both terminal or GUI interchangeably. For example, you can clone this repository using terminal commands and then once you open the project in your IDE it will automatically detect the `.git` folder and enable Git support.

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