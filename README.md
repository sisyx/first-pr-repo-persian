
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
<h2> سلام برنامه نویس  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px"></h2>
  <!-- <i>Let's help you submit your first pull request. Just follow the steps given below</i> -->
  <i>بیاید بهتون کمک کنیم اولین pull request تتون رو بفرستید. فقط قدم قدم مثل این پایین انجام بده.</i>
</div>

### قدم اول
اولین قدم برای شما جهت contribute کردن به یک پروژه ی متن باز اینه که اون رو **_fork_** کنید. این یک کپی از پروژه تحت حسابت میسازی.</br>

<!-- The first step you want to do in-order to contribute to an open source project is to **_fork_** the project. This will create a copy of the project under your account.<br> -->
یه دکمه ی fork در بالا و سمت راست صفحه هست. 
<!-- You'll see the fork option on the top right hand side of the screen. -->
- روی دکمه کلیک کن
<!-- - Click on the fork button. -->
<details open>
  <summary>Fork Button Image</summary>
  <summary>عکس دکمه ی fork</summary>
  <img src="https://github.com/nirbhayvashisht/first-pr-repo/blob/master/Resources/fork%20button.PNG" alt="fork button Image">
</details>

### Step 2
<!-- Now, you have to clone the forked repository. This will create a local copy of the project on your machine. -->
حالا، باید پروژه ی fork شده رو clone : این کار یه کپی داخلی از پروژه روی دستگاهت ایجاد میکنه.

You can do this in 2 ways:
دوتا راه برای این کاری داری

<details>
  <!-- <summary>Code Button and Clone Otions Image</summary> -->
  <summary>عکس دکمه و گزینه ی clone</summary>
  <img src="https://github.com/nirbhayvashisht/first-pr-repo/blob/master/Resources/clone%20link.PNG" alt="Code Button Image">
</details>

1. روش 1
  <!-- - Click on the clone button. -->
  - روی دکمه ی clone کلیک کن.
  <!-- - Download the ZIP and then extract it. -->
  - فایل زیپ رو دانلود و سپس اکسترکتش کن.
2. روش 2
  <!-- - Click on the clone button. -->
  - روی دتتکمه ی clone کلیک کن
  <!-- - Copy the link under HTTPS section. -->
  - لینک زیر قسمت HTTPS رو کپی کن
  <!-- - Open terminal/git bash/command prompt. -->
  - یه ترمینال/گیت بش/کامند پرامپت باز کن
  <!-- - Type - -->
  - بنویس
  ```
  git clone
  ```
  - حالا لینک کپی شده رو جایگذاری کن.
  - کامند نهایی باید پیزی شبیه به این باشد:
  ```
  git clone https://github.com/YOUR_USERNAME/first-pr-repo.git
  ```
<details>
  <summary>Cloning though git bash</summary>
  <summary>کلون کردن از طریق گیت بش</summary>
  <img src="https://github.com/nirbhayvashisht/first-pr-repo/blob/master/Resources/cloned.PNG" alt="fork button link">
</details>
  
### Step 3
<!-- Let's start working on the project now! -->
حالا بیا روی پروژه کار کنیم.
We need to change directory into cloned folder by typing the following command.
```
cd first-pr-repo
```
Now, BEFORE CHANGING ANYTHING, make sure you're working on a different branch and not in master. 
To create a new branch, from the terminal inside your current project directory type the following command.
```
git branch YOUR_GITHUB_USERNAME-profile
```
Obviously you'll have to replace the YOUR_GITHUB_USERNAME with your GitHub username.<br>
(You can give any name to your branch which describes the purpose of the branch. Since here we're adding your profile to the profiles directory, we'll simply give the name of the branch as above. 
eg: git branch nirbhayvashisht-profile. )<br>
Once you have created the new branch we'll change the current branch from master to your newly created branch.<br>
Execute the following command on your terminal.
```
git checkout YOUR_BRANCH_NAME
```
<details>
  <summary>It should look like this. (With your chosen names ofcourse)</summary>
  <img src="https://github.com/nirbhayvashisht/first-pr-repo/blob/master/Resources/branched.PNG" alt="Branching procedure">
</details>
  

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
<details>
  <summary>Your file should look something like this(With your names ofcourse</summary>
  <img src="https://github.com/nirbhayvashisht/first-pr-repo/blob/master/Resources/editing%20markdown.PNG" alt="markdown file image">
</details>

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
<details>
  <summary>Commiting Image</summary>
  <img src="https://github.com/nirbhayvashisht/first-pr-repo/blob/master/Resources/committed.PNG" alt="Commiting Image">
</details>


### Step 6
Let's push the changes to your repository on GitHub! 
Execute the following command to push all the changes to the forked copy in your GitHub account.
```
git push -u origin YOUR_BRANCH_NAME
```
### Step 7
Now open your github account to make a pull request.
- Click on compare and pull request.

<div align="center">
  <img src="https://github.com/nirbhayvashisht/first-pr-repo/blob/master/Resources/pr1.PNG" alt="pr button">
</div>
<br>

- Write a meaningful description and click on Create Pull Request.

<div align="center">
  <img src="https://github.com/nirbhayvashisht/first-pr-repo/blob/master/Resources/pr2.PNG">
</div>

<h2 align="center">Congratulations! You just created your first pull request🥳</h2>
  





  
