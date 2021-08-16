# Github Workflow Demostration

- [Why do we want to use Git?](#why-do-we-want-to-use-git)
- [What is Git?](#what-is-git)
- [Git vs. Github](#git-vs-github)
- [Git Commands vs. Github Desktop](#git-commands-vs-github-desktop)

- [1. Basic Shell Commands](#1-basic-shell-commands)
    + [1. **P**rint **C**urrent **D**irectory](#1-print-current-directory)
    + [2. **C**hange **D**irectory](#2-change-directory)
    + [3. **M**a**k**e **Dir**ectroy](#3-make-directroy)
    + [4. **M**o**v**e or rename files](#4-move-or-rename-files)
    + [5. **L**i**s**t (files)](#5-list-files)
- [2. Symbols](#2-symbols)
- [3. Github Setup (SSH)](#3-github-setup-ssh)
- [4. Using Git Verbs](#4-using-git-verbs)
    + [1. Fork: make a copy from other's repository](#1-fork-make-a-copy-from-others-repository)
    + [2. Clone: download everything in a repository](#2-clone-download-everything-in-a-repository)
    + [3. Status: check Git status](#3-status-check-git-status)
    + [3. Add: allow Git to track file changes](#3-add-allow-git-to-track-file-changes)
    + [4. Commit: submit a new version to Git](#4-commit-submit-a-new-version-to-git)
    + [5. Push: updating remote repository](#5-push-updating-remote-repository)
    + [<div style="color:red">**NEVER DO THIS Unless You Know What You Are Doing.** </div>](#never-do-this-unless-you-know-what-you-are-doing)
    + [6. Pull: updating local repository](#6-pull-updating-local-repository)
- [5. Pull Request (PR)](#5-pull-request-pr)
- [6. Practice](#6-practice)
- [7. Resources](#7-resources)




# Why do we want to use Git?
The following pictures are from: [連猴子都能懂的Git入門指南](https://backlog.com/git-tutorial/tw/)

</br>
<div style="text-align:center;font-weight:bold;">

![Problem 1: Chaotic Namings and Versions of Files](https://backlog.com/git-tutorial/tw/img/post/intro/capture_intro1_1_1.png)

Problem 1: Chaotic Namings and Versions of Files

</br>

![Problem 2: Conflicts When Collaborating on the Same Files](https://backlog.com/git-tutorial/tw/img/post/intro/capture_intro1_1_2.png)

Problem 2: Conflicts When Collaborating on the Same Files

</br>


![Git: Preserving File Versions and Raising Warnings When Modifying the Same Files](https://backlog.com/git-tutorial/tw/img/post/intro/capture_intro1_1_3.png)

Git: Preserving File Versions and Raising Warnings When Modifying the Same Files

</div>

# What is Git?

### **Git is a distributed version control system**

<br>

The following pictures are from: [Manisha Basra](https://medium.com/swlh/things-about-git-and-github-you-need-to-know-as-developer-907baa0bed79)

### 1.
<div style="text-align:center;font-weight:bold;">

![Distributed Version Control System](./img/distributed-version-control-system.png)

Distributed Version Control System

</div >


### 2.

<div style="text-align:center;font-weight:bold;">

![Distributed Version Control](./img/distributed-version-control.png)

Distributed Version Control System

</div>




# Git vs. Github
From the [Stackoverflow](https://stackoverflow.com/questions/13321556/difference-between-git-and-github):

1. Git is a revision (or version) control system, a tool to manage your source code history.

2. GitHub is a hosting service for Git repositories.

3. So they are not the same thing: Git is the tool, GitHub is the service for projects that use Git.

</br>

# Git Commands vs. [Github Desktop](https://desktop.github.com)

### Both are able to do the same things, but using commands will be a lot faster than using Github Desktop.

</br>

# 1. Basic Shell Commands

### 1. **P**rint **C**urrent **D**irectory
```bash
pwd
```

### 2. **C**hange **D**irectory
```bash
cd your/file/path/
```

###  3. **M**a**k**e **Dir**ectroy
```bash
mkdir your/folder/name
```

### 4. **M**o**v**e or rename files

```bash 
# move files
mv your/path/origin_name your/other/path/origin_name
```

```bash 
# rename files
mv origin_name modified_name
```

### 5. **L**i**s**t (files)
```bash
ls your/directory/
```

# 2. Symbols
```bash
/ # root directory
~ # home directory
. # current directory
```


# 3. Github Setup (SSH)


### 1. Check if SSH public key exists
```bash
ls ~/.ssh
```
### 2. If **not**, type:
```bash
ssh-keygen
```

### 3. Copy your ssh key to Github
```bash
# For Mac
pbcopy < ~/.ssh/your.pub 
```

```powershell
# For Windows
clip < ~/.ssh/your.pub
```

1. Click your profile picture and find **Settings**.

    ![settings](./img/settings.png)


2. Click **SSH and GPG keys** on the left hand side.

    ![ssh-gpg-keys](./img/ssh-gpg-keys.png)


3. Click **New SSH Keys**

    ![new-ssh-keys](./img/new-ssh-key.png)

4. Click **Add SSH key** after filling out the form

    ![add-ssh-keys](./img/add-ssh-keys.png)



# 4. Using Git Verbs


### 1. Fork: make a copy from other's repository

![Fork](./img/fork.png)

### 2. Clone: download everything in a repository

```bash
git clone git@github.com:NTU-Speech-Motor-Control-Lab/github-demo.git
```

### 3. Status: check Git status

```bash
git status
```

### 3. Add: allow Git to track file changes

```bash
git add your-file-name
```

```bash
git add .
```

### 4. Commit: submit a new version to Git

```bash
git commit -m "your commit message"
```

### 5. Push: updating remote repository

```bash
git push 
```

### <span style="color:red">**NEVER DO THIS Unless You Know What You Are Doing.** </span>
```bash
git push -f
```


### 6. Pull: updating local repository
```
git pull 
```

# 5. Pull Request (PR)

### 1. 

![Pull-request](./img/pull-request.png)

### 2. 

![New-Pull-Request-Button](./img/pr-button.png)

### 3.

![Create pull request](./img/create-pull-request.png)

### 4.

![Open pull request](./img/open-pull-request.gif)

# 6. Practice

## Add your name and github account below.

*


# 7. Resources

[W3HexShool](https://w3c.hexschool.com/git/fd426d5a) 

[連猴子都能懂的Git入門指南](https://backlog.com/git-tutorial/tw/)

