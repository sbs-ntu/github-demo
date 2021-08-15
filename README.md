# Git vs. Github
From [stackoverflow](https://stackoverflow.com/questions/13321556/difference-between-git-and-github):

1. Git is a revision (or version) control system, a tool to manage your source code history.

2. GitHub is a hosting service for Git repositories.

3. So they are not the same thing: Git is the tool, GitHub is the service for projects that use Git.

</br>

# Git Command vs. [Github Desktop](https://desktop.github.com)

### Both are able to do the same thing, but using commands will be a lot faster than using Github Desktop.

</br>

# 1. Basic Shell Commands

### 1. <strong>P</strong>rint <strong>C</strong>urrent <strong>D</strong>irectory
```bash
pwd
```

### 2. <strong>C</strong>hange <strong>D</strong>irectory
```bash
cd your/file/path/
```

###  3. <strong>M</strong>a<strong>k</strong>e <strong>Dir</strong>ectroy
```bash
mkdir your/folder/name
```

### 4. <strong>M</strong>o<strong>v</strong>e or rename files

```bash 
# move files
mv your/path/origin_name your/other/path/origin_name
```

```bash 
# rename files
mv origin_name modified_name
```

### 5. <strong>L</strong>i<strong>s</strong>t (files)
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


### 1. Check if ssh public key exists
```bash
ls ~/.ssh
```
### 2. If <strong>Not</strong>, type:
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


# 4. Using Git

### 1. Fork

![Fork](./img/fork.png)

### 2. Clone

```bash
git clone git@github.com:NTU-Speech-Motor-Control-Lab/github-demo.git
```

### 3. Add

```bash
git add your-file-name
```

```bash
git add .
```

### 4. Commit

```bash
git commit -m "your commit message"
```

### 5. Push

```bash
git push 
```

### <div style="color:red">**NEVER DO THIS unless you know what you are doing.** </div>
```bash
git push -f
```


### 6. Pull
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
