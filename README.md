<h1 align="center">MasteringGit</h1>

<div style="text-align:center">

![GitHub commit activity](https://img.shields.io/github/commit-activity/m/techclassltd/MasteringGit)
[![GitHub last commit](https://img.shields.io/github/last-commit/techclassltd/MasteringGit)](https://github.com/techclassltd/MasteringGit)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/techclassltd/MasteringGit)](https://github.com/techclassltd/MasteringGit/pulls)
[![GitHub forks](https://img.shields.io/github/forks/techclassltd/MasteringGit)](https://github.com/techclassltd/MasteringGit/network)
[![GitHub contributors](https://img.shields.io/github/contributors-anon/techclassltd/MasteringGit?color=orange&label=contributors)](https://github.com/techclassltd/MasteringGit)
[![GitHub stars](https://img.shields.io/github/stars/techclassltd/MasteringGit)](https://github.com/techclassltd/MasteringGit/stargazers)

</div>

## 📝 Table of Contents

1. [About](#about)
    * [Requisites](#requisites)
    * [Limitations](#limitations)
2. [Getting Started](#getting-started)
    * [Reminders](#reminders)
    * [Local Setup](#setup)
3. [Usage](#usage)
4. [Tree](#tree)
5. [Author](#author)
6. [Show your support](#support)


## 🔰 About <a name="about"></a>

Welcome to the concluding portion on introducing the concepts of working with version control using Git. The purpose of this exercise is to apply the common usage and workaround of version control in creating collaborative material using Git as a version control system. Where the students are assigned to get a local copy of the project from a remote repository on Github, creating a branch, updating a particular file, committing, mergin branches, pushing and undoing.

MasteringGit project is based on the content from the subject [Mastering Version Control with Git TT00CR85](https://hakija.oma.metropolia.fi/#1882) delivered by [TechClass](https://techclass.com/products/version-control-with-git-course) and offered by the [Metropolia Open University of Applied Sciences](https://hakija.oma.metropolia.fi/#1882) and [Amkoodari project (2019-2021)](https://amkoodari.fi/en).

### 🔑 Requisites <a name="requisites"></a>

- Enrolled students to the [course](https://techclass.com/products/version-control-with-git-course) who already done with all of the tasks except this one.

- [Install Git](http://git-scm.com/downloads) and basic Git command know-how.

  ```bash
  # verify your installation
  $ git --version
  # e.g. output
  git version 2.25.1
  ```

- Preferred text editor/IDE. There are many to choose from.

- Familiarity in using the command prompt or terminal.


### ⛓️ Limitations <a name="limitations"></a>

This documentation serves as an additional guidelines only to start and complete the MasteringGit project as a requirement to pass the subject _Mastering Version Control with Git_ and will **not disclose** any Git command necessary to implement successfully the project locally/remotely. It is part of the challenges for the student to resolve their issues and fulfill the requirements needed.

If you're stuck, go back again to the previous lessons from the TechClass platform, look for answers by yourself on the internet, you can also ask a friend/classmate who knows the subject matter for help, and lastly message the course instructor for additional assistance.


## 🏁 Getting Started <a name="getting-started"></a>

<div style="text-align: justify">

### ⛑️ Reminders: <a name="reminders"></a>

* Read thoroughly the directions from the **final project section** of the [Version Control with Git](https://techclass.com/products/version-control-with-git-course) course by signing in to the [TechClass platform](https://techclass.com/).

* Send a message to the course instructor to add you as a contributor to the project and append your **Github username** to your message. You can send your message through the messaging app of [Version Control with Git course](https://techclass.com/collections/data-science-courses) by logging in to [TechClass](https://techclass.com/). 

* Remember to take a screenshot of all the required steps that you implemented locally to be attached later on to the platform.

### 🏗️ Local Setup <a name="setup"></a>

1. Configure your Git username and email globally or locally.

2. Clone the [upstream repository](https://github.com/techclassltd/MasteringGit) and define your local project folder as "MasteringGit-YourStudentID".

3. `cd` to your project folder and create a local `branch`, name it based on your **student ID**.

## 🧩 Usage <a name="usage"></a>

1. Start making changes to the following files and subdirectories on the local branch that you created(refrain from working on the master branch). Firstly, update the _answers.txt_ file by listing your answer at the bottom of the file. Enter your **student ID**, **your name** and return the following 3 questions. E.g.

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


* Count the number of students who listed their answers in the **answers.txt** file(inc. yourself). Disregard the number of student entries from **Lists/Students directories** as those entries have been archive since 2016.

* Count the occurrence of "Student ID" or "ID" using the `Cntrl+F`(on your text editor) or `grep` command can be an option to ease in counting the number of students from the list.

**In consideration for the next committers, delete all your markers or conflict block(if any) from the answers.txt to keep the file neat**. 

2. Navigate to _Lists/Students_ diirectories then make a directory, define it according to your student ID/number and inside of the created directory create a _cities.txt_ file. You can optionally add a description or a list to this file or leave the file empty.

3. Stage and commit your changes. 
 
4. View the status and log.    

5. Before pushing it back to the [upstream repository](https://github.com/techclassltd/MasteringGit), **ensure that the local master branch is synchronized and has all of the updates from the upstream** using pull. Then checkout to your source branch and `merge` from the updated local master.

6. Ignore some types of files.

7. Push the changes to GitHub.

8. Edit answers.txt.
   
9. Compare the changes.   
  
10. Undo the modification. 
   
11. Tag the last commit.

</div>


## 🌱 Tree <a name="tree"></a>

```
.
├── answers.txt
├── LICENSE
├── Lists
│   └── Students
│       ├── # Student DIRS
│       │   └── cities.txt
│       ├── ...
│       │   └── cities.txt
│       ├── ...
│       │   └── cities.txt
│       ├── ...
│       │   └── cities.txt
│       ├── ...
│       │   └── cities.txt
│       ├── ...
│       ├── ...
│       ├── ...
│       ├── ...
│       ├── ...
│       ├── ...
|
└── README.md

```

## ✍️ Author <a name="author"></a>

- [@techclassltd](https://github.com/techclassltd) - Idea, initial work & course instructor

See also the list of [contributors](https://github.com/techclassltd/MasteringGit/graphs/contributors) to this project.


## 🎗️ Show your support <a name="support"></a>

- Give a ⭐️ if this project helped you!
