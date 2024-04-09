<h1 align="center">این ریپازیتوری به شما کمک میکنه اولین pull request تون رو بفرستید</h1>

<div align="center">
  <a href="https://github.com/sisyx/first-pr-repo-persian/stargazers"><img src="https://img.shields.io/github/stars/nirbhayvashisht/first-pr-repo" alt="repo stars"></a>
  <a href="https://github.com/sisyx/first-pr-repo-persiab/network/members"><img src="https://img.shields.io/github/forks/nirbhayvashisht/first-pr-repo" alt="forks badge"></a>
  <a href="https://github.com/sisyx/first-pr-repo-persian/pulls"><img src="https://img.shields.io/github/issues-pr/nirbhayvashisht/first-pr-repo" alt="pull requests badge"></a>
  <a href="https://github.com/sisyx/first-pr-repo-persian/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues-raw/nirbhayvashisht/first-pr-repo"></a>
  <a href="https://github.com/sisyx/first-pr-repo-persian/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/nirbhayvashisht/first-pr-repo"></a>
  <a href="https://github.com/sisyx/first-pr-repo-persian/blob/master/LICENSE"><img alt="GitHub" src="https://img.shields.io/github/license/nirbhayvashisht/first-pr-repo"></a>
</div>

<div align="center">
<h2> سلام برنامه نویس  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px"></h2>
  <!-- <i>Let's help you submit your first pull request. Just follow the steps given below</i> -->
  <i>بیاید بهتون کمک کنیم اولین pull request تتون رو بفرستید. فقط قدم قدم مثل این پایین انجام بده.</i>
</div>

### قدم اول
اولین قدم برای شما جهت contribute کردن به یک پروژه ی متن باز اینه که اون رو **_fork_** کنید. این کار یک کپی از پروژه تحت حسابتون میسازه..</br>

<!-- The first step you want to do in-order to contribute to an open source project is to **_fork_** the project. This will create a copy of the project under your account.<br> -->
یه دکمه ی fork در بالا و سمت راست صفحه هست. 
<!-- You'll see the fork option on the top right hand side of the screen. -->
- روی دکمه کلیک کنید
<!-- - Click on the fork button. -->
<details open>
  <!-- <summary>Fork Button Image</summary> -->
  <summary>عکس دکمه ی fork</summary>
  <img src="https://github.com/nirbhayvashisht/first-pr-repo/blob/master/Resources/fork%20button.PNG" alt="fork button Image">
</details>

### قدم دوم
<!-- Now, you have to clone the forked repository. This will create a local copy of the project on your machine. -->
حالا، باید پروژه ی fork شده رو clone کنید : این کار یه کپی داخلی از پروژه روی دستگاهتون ایجاد میکنه.

<!-- You can do this in 2 ways: -->
دوتا راه برای این کاری دارین

<details>
  <!-- <summary>Code Button and Clone Otions Image</summary> -->
  <summary>عکس دکمه و گزینه ی clone</summary>
  <img src="https://github.com/nirbhayvashisht/first-pr-repo/blob/master/Resources/clone%20link.PNG" alt="Code Button Image">
</details>

1. روش 1
  <!-- - Click on the clone button. -->
  - روی دکمه ی clone کلیک کنید.
  <!-- - Download the ZIP and then extract it. -->
  - فایل زیپ رو دانلود و سپس استخراجش کنید.
2. روش 2
  <!-- - Click on the clone button. -->
  - روی دکمه ی clone کلیک کنید
  <!-- - Copy the link under HTTPS section. -->
  - لینک زیر قسمت HTTPS رو کپی کنید.
  <!-- - Open terminal/git bash/command prompt. -->
  - یه ترمینال/گیت بش/کامند پرامپت باز کنید.
  <!-- - Type - -->
  - تایپ کنید:
  ```
  git clone
  ```
  - حالا لینک کپی شده رو جایگذاری کنید.
  - کامند نهایی باید پیزی شبیه به این باشد:
  ```
  git clone https://github.com/YOUR_USERNAME/first-pr-repo.git
  ```
<details>
  <!-- <summary>Cloning though git bash</sujmmary> -->
  <summary>کلون کردن از طریق گیت بش</summary>
  <img src="https://github.com/nirbhayvashisht/first-pr-repo/blob/master/Resources/cloned.PNG" alt="fork button link">
</details>
  
### قدم سوم
<!-- Let's start working on the project now! -->
حالا بیا روی پروژه کار کنیم.
<!-- We need to change directory into cloned folder by typing the following command. -->
ما باید با کامند زیر دایرکتوری رو به دایرکتوری clone شده تغییر بدیم
```
cd first-pr-repo-persian
```
<!-- Now, BEFORE CHANGING ANYTHING, make sure you're working on a different branch and not in master. --> 
حالا، قبل از هر تغییری، مطمین بشید که روی شاخه(branch) دیگری غیر از master هستید.
<!-- To create a new branch, from the terminal inside your current project directory tygpe the following command. -->
برای ساخت یه branch جدید، ااز یه ترمینال در دایرکتوری فعلی کامند زیر رو تایپ کنید.
```
git branch YOUR_GITHUB_USERNAME-profile
```
<!-- Obviously you'll have to replace the YOUR_GITHUB_USERNAME with your GitHub username.<br> -->
واضحه که باید به جای YOUR_GITHUB_USERNAME اسم خودتون در گیتهاب رو بنویسید.<br>
وقتی branch چدید رو ساختید ما branch رو از master به branch جدید تغییر میدیم.
کامند زیر را در ترمینال اجرا کنید.
```
git checkout YOUR_BRANCH_NAME
```
<details>
  <!-- <summary>It should look like this. (With your chosen names ofcourse)</summary> -->
  <summary>باید چیزی شبیه به این باشد. (البته با اسم دلخواه خودتون)</summary>
  <img src="https://github.com/nirbhayvashisht/first-pr-repo/blob/master/Resources/branched.PNG" alt="Branching procedure">
</details>
  

### قدم چهارم
<!-- - Move into the profiles directory in cloned project. -->
- برید به دایرکتوری profile از پروژه ی clone شده
```
cd profiles
```
<!-- - Create a new file called YOUR_USERNAME.md using the following comman/d. -->
- یک فایل جدید به عنوان YOUR_USERNAME.md با استفاده از کامند زیر بسازید.
```
touch YOUR_USERNAME.md
```
<!-- - Navigate into the project directory (through your file manager) and open this file in your favourite editor. -->
- برید به دایرکتوری پروژه (با فایل منیجرتون) و فایل رو با ادیتور دلخواهتون ویرایش کنید.
<!-- - fill the details as shown below: -->
- جزییات رو به شکل زیر بنویسید
```
---
username: YOUR_USER_NAME
fullname: YOUR_FULL_NAME
---
```
<!-- - Save and clone the file.<br> -->
- فایل را ذخیره کنید. <br>
<details>
  <!-- <summary>Your file should look something like this(With your names ofcourse</summary> -->
  <summary>فایل شما باید چیزی شبیه به این باشد. (با اسم شما البته) </summary>
  <img src="https://github.com/nirbhayvashisht/first-pr-repo/blob/master/Resources/editing%20markdown.PNG" alt="markdown file image">
</details>

<!-- **NOTE**: This is just a way of simulating - you making changes into the project file. --> 
**نکته**: این تنها یک شبیه سازی است - شما دارید تغییراتی در فایل پروژه ایجاد میکنید.
### قدم پنجم
<!-- - Now we need to stage all the changes we made. --> 
- حالا باید همه ی تغییرات را stage کنیم.
<!-- - Open the terminal again and inside the project directory and execute following commands. -->
- دوباره یک ترمینال باز کنید و درون دایرکتوری پروژه کامندهای زیر رو اجرا کنید.
```
git add .
```
<!-- - The above command staged all the changes, now we need to commit them with a suitable message. You can commit using the following command. -->
- کامند بالا همه ی تغییر ها را در حالت stage قرار داد، حالا باید با یه پیام مناسب commit کنیم. شما میتونید از کامند زیر استفاده کنید.
```
git commit -m "YOUR_COMMIT_MESSAGE"
```
مثال:
```
git commit -m "Hey, I just added my profile in the profiles directory"
```
<details>
  <summary>عکس commit کردن</summary>
  <img src="https://github.com/nirbhayvashisht/first-pr-repo/blob/master/Resources/committed.PNG" alt="Commiting Image">
</details>


### قدم ششم
<!-- Let's push the changes to your repository on GitHub! --> 
حالا بیاید تغییرات را در ریپازیتوری گیتهابتون ذخیره گنیم
<!-- Execute the following command to push all the changes to the forked copy in ygour GitHub account. -->
کامند زیر را اجرا کنید تا همه ی تغییرات را در ریپازیتوری fork شده ذخیره کنید.
```
git push -u origin YOUR_BRANCH_NAME
```
### قدم هفتم
<!-- Now open your github account to make a pull request. -->
حالا گیتهابتون رو باز کنید و یک pull request ایجاد کنید
<!-- - Click on compare and pull request. -->
- روی دکمه ی compare and pull request کلیک کنید.

<div align="center">
  <img src="https://github.com/nirbhayvashisht/first-pr-repo/blob/master/Resources/pr1.PNG" alt="pr button">
</div>
<br>
<!-- - Write a meaningful description and click on Create Pull Request. -->
- یک توضیح با معنی بنویسید و روی دکمه ی Create Pull Request کلیک کنید.
<div align="center">
  <img src="https://github.com/nirbhayvashisht/first-pr-repo/blob/master/Resources/pr2.PNG">
</div>

<h2 align="center">تبریک. شما اولین Pull Request خود را ارسال کردید.🥳</h2>
