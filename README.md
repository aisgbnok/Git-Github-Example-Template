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

### 2. Basic Git Commands

We have successfully generated our own repository from a template, and we have just cloned it to our
local computer. Now that Git and GitHub are set up and connected we can let them fade into the
background and do their job. Well not exactly, but sort of.

All of this might be confusing now, and that's okay. As you continue to use Git and GitHub they will
slowly start feeling less like a chore and more like a companion aiding your development journeys.

Let's go over some basic Git commands to get started.

#### Status

[Provides repository status,](https://git-scm.com/docs/git-status) like if your working space is
up-to-date with your local repository, etc.

```
git status
```

#### Fetch

[Downloads all the changes from the remote repositories like GitHub's server.](https://git-scm.com/docs/git-fetch)
This will basically tell your local repository about everything on the GitHub server without
actually applying it to your current working space.

```
git fetch
```

#### Add

[Add files to the index and staging area.](https://git-scm.com/docs/git-fetch) Git will
automatically track what has changed in your repository, but before you can commit them you need to
tell Git what files to commit. This is done by adding them to the staging area.

You can run the `status` command to see what has changed. Then you can add them to your staging
area.

```
git add <filename/directory>
```

#### Pull

...

### 3. Change your `README`

Let's make our first commit...

#### Add your name to Author Section

> This `README.md` is a markdown file. Markdown files are text files with some basic formatting
> abilities. Markdown files have a `.md` file extension and are widely used by developers for
> documentation.

For our first commit we will do something really simple. Let's add your name to the author section!




> Make a commit.

### 4. Add another Markdown File

Add another markdown file and make a commit.