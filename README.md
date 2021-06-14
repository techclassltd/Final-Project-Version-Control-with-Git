<h1 align="center">MasteringGit</h1>

<div style="text-align:center">

![GitHub commit activity](https://img.shields.io/github/commit-activity/m/farhad85/MasteringGit)
![GitHub last commit](https://img.shields.io/github/last-commit/farhad85/MasteringGit)
![GitHub pull requests](https://img.shields.io/github/issues-pr/farhad85/MasteringGit)
[![GitHub forks](https://img.shields.io/github/forks/farhad85/MasteringGit)](https://github.com/farhad85/MasteringGit/network)
![GitHub contributors](https://img.shields.io/github/contributors-anon/farhad85/MasteringGit)
[![GitHub stars](https://img.shields.io/github/stars/farhad85/MasteringGit)](https://github.com/farhad85/MasteringGit/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/farhad85/MasteringGit)](https://github.com/farhad85/MasteringGit/issues)
[![GitHub license](https://img.shields.io/github/license/farhad85/MasteringGit?color=9cf)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Twitter](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fgithub.com%2Ffarhad85%2FMasteringGit)](https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2Ffarhad85%2FMasteringGit)

</div>

## 📝 Table of Contents

1. [About](#about)
    - [Limitations](#limitations)
2. [General Instructions](#general-instructions)
    - [Requisites](#requisites)
3. [Tree](#tree)
4. [Author](#author)
    - [List of contributors](#contributors)
5. [Show your support](#support)
6. [License](#license)

## ⚙️ About <a name="about"></a>

Welcome to the concluding portion on introducing the concepts of working with version control using Git. The purpose of this exercise is to apply the common usage and workaround of version control in creating collaborative material using Git as a version control system. Where the students are assigned to get a local copy of the project from a remote repository on Github, form a branch, update a particular file, append a file, stage changes for the upcoming commits, perform a pull request for review and with the likelihood to be merged to the master branch if there is no conflict.

MasteringGit project is based on the content from the subject [Mastering Version Control with Git TT00CR85](https://hakija.oma.metropolia.fi/#1882) delivered by [TechClass](https://techclass.com/academy/courses/1) and offered by the [Metropolia Open University of Applied Sciences](https://hakija.oma.metropolia.fi/#1882) and [Amkoodari project (2019-2021)](https://amkoodari.fi/en).

### ⛓️ Limitations <a name="limitations"></a>

This documentation serves as an additional guidelines only to start and complete the MasteringGit project as a requirement to pass the subject _Mastering Version Control with Git_ and will **not disclose** any Git command necessary to implement successfully the project on your local machine. It is part of the challenges for the student to resolve their issues and fulfill the requirements needed.

If you're stuck, go back again to the previous lessons from the TechClass platform, look for answers by yourself on the internet, you can also ask a friend/classmate who knows the subject matter for help, and lastly message the course instructor for additional assistance.

## 🪜 General Instructions <a name="general-instructions"></a>

<div style="text-align: justify">

Read thoroughly the directions from the **final project section** of the _Version Control with Git_ course by signing in to the [TechClass platform](https://techclass.com/). _Don't foreget to take a screen shot of all the steps that you implement on your local machine to be attached later on the platform_.

1. While still logged in to the **Version Control with Git** course platform in TechClass, send a message to the course instructor appending your **Github username** requesting to add you as a contributor to the project. Failure to do this step will permission deny your local branch to push in the remote repository later on 😮.

   ```bash
   remote: Permission to farhad85/MasteringGit.git denied to samplegithubusername.
   fatal: unable to access 'https://github.com/farhad85/MasteringGit.git/': The requested URL returned error: 403
   ```

   _Regulary check your email inbox associated with your Github account to accept the invitation from the course instructor_.

2. Configure your Git username and email globally or locally.

3. Get a local copy of the project via this link: https://github.com/farhad85/MasteringGit. You can also fork the repo if you want to experiment freely with the project.

4. Open your local copy of the project and create a `branch`(<span style="color:red">refrain from working on master branch</span>). It is recommended to add your student ID/number to name of your local branch.

5. Open your local copy of the project and start making changes to the following files and subdirectories. Firstly, update the _answers.txt_ file by listing your answer at the bottom of the file. Enter your **student ID**, **your name** and return the following 3 questions. E.g.

   ```bash
   Student ID:1234567
   Name: Amber Alert
   Question 1.
   Your favorite color: Purple

   Question 2.
   Your favorite sport: Uneven bars gymnastics

   Question 3.
   Your favorite food: Muffuletta

   ```

   From the top of the file, update the **number of students who modified this file(count except the template example)** and **name of the student who modified this file(include your name)**. E.g.

   ```bash
   Number of students who modified this file: 111 students

   Name of the last student who modified this file: Amber Alert

   ```

6. Go to _Lists/Students_ then make a directory, name it according to your student ID/number and inside of the created directory create a _cities.txt_ file. You can optionally add a description or a list to this file or leave the file empty. Finally, save your changes for staging.

7. Add your commit and push it back to the remote repository.

8. Login to your **Github account** and click _Compare & pull request_ button of the project remote repository then click _Create pull request_ to open a new pull request.

9. Wait until authorized contributor/s merge your branch to **master**.

</div>

### 🔑 Requisites <a name="requisites"></a>

- Enrolled student to the [course](https://techclass.com/academy/courses/1) who already done with all of the tasks except this one.

- [Install Git](http://git-scm.com/downloads) and basic Git command know-how.

  ```bash
  # verify your installation
  $ git --version
  # e.g. output
  git version 2.25.1
  ```

- Your preferred text editor/IDE. There are many to choose from.

- Knowledge about command line interface or terminal.

- [Github](https://github.com/) user account.

## 🌱 Tree <a name="tree"></a>

```bash
├── answers.txt
├── .gitignore
├── LICENSE
├── Lists
│   └── Students
│       ├── 007
│       ├── 020283
│       ├── 123
│       ├── 1234
│       ├── 12345
│       ├── 12354
│       ├── 1300068
│       ├── 1302141
│       ├── 1304948
│       ├── 1304950
│       ├── 1304977
│       ├── 1304980
│       ├── 1305012
│       ├── 1305914
│       ├── 1305923
│       ├── 1305934
│       ├── 1306663
│       ├── 1337
│       ├── 1400162
│       ├── 1402081
│       ├── 1404065
│       ├── 147258369
│       ├── 1501104
│       ├── 1502366
│       ├── 1504160
│       ├── 1504166
│       ├── 1504211
│       ├── 1504229
│       ├── 1505610
│       ├── 1505903
│       ├── 1602068
│       ├── 1602383
│       ├── 1602438
│       ├── 1602926
│       ├── 1605465
│       ├── 1605534
│       ├── 1610
│       ├── 1700380
│       ├── 1700908
│       ├── 1701663
│       ├── 1701791
│       ├── 1701880
│       ├── 1702658
│       ├── 1703144
│       ├── 1705010
│       ├── 1708131
│       ├── 1708500
│       ├── 1708501
│       ├── 1708593
│       ├── 1708601
│       ├── 1708636
│       ├── 1708918
│       ├── 1800717
│       ├── 1801670
│       ├── 1802259
│       ├── 1802994
│       ├── 1803395
│       ├── 1804293
│       ├── 1804770
│       ├── 1808804
│       ├── 1809477
│       ├── 1907019
│       ├── 1914372
│       ├── 192876
│       ├── 2006895
│       ├── 2007077
│       ├── 2016365
│       ├── 2016374
│       ├── 2018254
│       ├── 2018746
│       ├── 202101291700
│       ├── 206602
│       ├── 210292
│       ├── 2102990
│       ├── 2108713
│       ├── 2131011
│       ├── 28031992
│       ├── 3141592653589
│       ├── 41
│       ├── 5084975
│       ├── 897491
│       ├── a1504542
│       ├── a1600607
│       ├── a1600792
│       ├── a1602782
│       ├── a1700433
│       ├── a1703080
│       ├── a1704510
│       ├── anh-vumartell
│       ├── b4bisu
│       ├── EijaP
│       ├── GIT001
│       ├── Gleb Tishchenko
│       ├── hectorm
│       ├── HH1803844
│       ├── Juha-Paananen
│       ├── jyleskin
│       ├── K1411
│       ├── K4424
│       ├── K4871
│       ├── K8241
│       ├── matti1511
│       ├── minh1401371
│       ├── N2723
│       ├── ojuse011
│       ├── Omar Abdelfattah
│       ├── pekko.sams
│       ├── Petri_Palmu
│       ├── S704396
│       ├── saraalka
│       ├── stanley_festus
│       ├── syloas
│       ├── t4ngth00
│       ├── t5pyan00
│       ├── Tapsa67
│       ├── TomiLehto
│       ├── tramnguyen
│       ├── vami67
│       └── Ville_Savolainen
└── README.md
```

## 🧠 Author <a name="author"></a>

- [@farhad85](https://github.com/farhad85) - Idea, initial work & course instructor

### ✍️ List of contributors <a name="contributors"></a>

<a href="https://github.com/farhad85/MasteringGit/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=farhad85/MasteringGit" />
</a>

## ✊ Show your support <a name="support"></a>

- Give a ⭐️ if this project helped you!

## ⚖️ License <a name="license"></a>

This project is [Creative Commons Zero v1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) licensed.
