<h1 align="center">This Repository will help people make their first Pull Request</h1>

<div align="center">
  <a href="https://github.com/nirbhayvashisht/first-pr-repo/stargazers"><img src="https://img.shields.io/github/stars/nirbhayvashisht/first-pr-repo" alt="repo stars"></a>
  <a href="https://github.com/nirbhayvashisht/first-pr-repo/network/members"><img src="https://img.shields.io/github/forks/nirbhayvashisht/first-pr-repo" alt="forks badge"></a>
  <a href="https://github.com/nirbhayvashisht/first-pr-repo/pulls"><img src="https://img.shields.io/github/issues-pr/nirbhayvashisht/first-pr-repo" alt="pull requests badge"></a>
  <a href="https://github.com/nirbhayvashisht/first-pr-repo/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues-raw/nirbhayvashisht/first-pr-repo"></a>
  <a href="https://github.com/nirbhayvashisht/first-pr-repo/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/nirbhayvashisht/first-pr-repo"></a>
  <a href="https://github.com/nirbhayvashisht/first-pr-repo/blob/master/LICENSE"><img alt="GitHub" src="https://img.shields.io/github/license/nirbhayvashisht/first-pr-repo"></a>
</div>

<div align="center">
<h2> Hello Developer  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px"></h2>
  <i>Let's help you submit your first pull request. Just follow the steps given below</i>
</div>

### Step 1
The first step you want to do in-order to contribute to an open source project is to **_fork_** the project. This will create a copy of the project under your account.
You'll see the fork option on the top right hand side of the screen.

### Step 2
Now, you have to clone the forked repository. This will create a local copy of the project on your machine.
You can do this in 2 ways:
1. OPTION 1
  - Click on the clone button
  - Download the ZIP and then extract it.
2. OPTION 2
  - Click on the clone button.
  - Copy the link under HTTPS section.
  - Open terminal/git bash/command prompt
  - Type 
  ```
  git clone
  ```
  - Now paste the link.
  - The resulting command should look something like this:
  ```
  git clone https://github.com/YOUR_USERNAME/first-pr-repo.git
  ```
  
### Step 3
Let's start working on the project now! 
We need to change directory into cloned folder by typing the following command.
```
cd first-pr-repo
```
Now, BEFORE CHANGINF ANYTHING, make sure you're working on a different branch and not in master. 
To create a new branch, from the terminal inside your current project directory type the following command.
```
git branch YOUR_GITHUB_USERNAME-profile
```
Obviously you'll have to replace the YOUR_GITHUB_USERNAME with your GitHub username.
(You can give any name to your branch which describes the purpose of the branch. Since here we're adding your profile to the profiles directory, we'll simply give the name of the branch as above. 
eg: git branch nirbhayvashisht-profile. 
Once you have created the new branch we'll change the current branch from master to your newly created branch. 
Execute the following command on your terminal.
```
git checkout YOUR_BRANCH_NAME
```

### Step 4
- Move into the profiles directory in cloned project.
```
cd profiles
```
- Create a new file called YOUR_USERNAME.md using the following command.
```
touch YOUR_USERNAME.md
```
- Navigate into the project directory (through your file manager) and open this file in your favourite editor.
- fill the details as shown below:
```
---
username: YOUR_USER_NAME
fullname: YOUR_FULL_NAME
---
```
- Save and clone the file.<br>
**NOTE**: This is just a way of simulating - you making changes into the project file. 

### Step 5
- Now we need to stage all the changes we made. 
- Open the terminal again and inside the project directory and execute following commands.
```
git add .
```
- The above command staged all the changes, now we need to commit them with a suitable message. You can commit using the following command.
```
git commit -m "YOUR_COMMIT_MESSAGE"
```
Example:
```
git commit -m "Hey, I just added my profile in the profiles directory"
```

### Step 6
Let's push the changes to your repository on GitHub! 
Execute the following command to push all the changes to the forked copy in your GitHub account.
```
git push -u origin YOUR_BRANCH_NAME
```
### Step 7
Now open your github account to make a pull request






  
