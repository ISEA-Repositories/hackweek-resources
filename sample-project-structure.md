# Sample Project Repository

This is an example of how teams can structure their project repositories and format their project README.md file.

## Files and folders in your project repository

This template provides the following suggested organizaiton structure for the project repository, but each project team is free to organize their repository as they see fit.

* **`contributors/`**
Each team member can create their own folder under contributors, within which they can work on their own scripts, notebooks, and other files. Having a dedicated folder for each person helps to prevent conflicts when merging with the main branch. This is a good place for team members to start off exploring data and methods for the project.

* **`data/`**
Data for the project should go in here.

* **`deliverables/`**
Codes, data analysis results, reports that are considered delivered results for the project should go in here.

* **`shared/`**
Code or notebooks that is shared by the team should go in here. These will be files such as Colab notebooks, Python scripts (.py), qualitative coding notebooks and so on.

* `.gitignore`
This file sets the files that will be globally ignored by `git` for the project. (e.g. you may want git to ignore temporary files or large data files, [read more about ignoring files here](https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files)).

* `README.md`
Description of the project (see suggested headings below).

* `model-card.md`
Description (following a metadata standard) of any machine learning models used in the project.

# Recommended content for your README.md file:

(you can remove the content here and above from your final project README.md file so that it begins with the Project or Team Name title below)

# Project or Team Name

## Project Title and Introduction

Provide a brief introduction describing the proposed work. Be sure to also decribe what skills team members will get to learn and practice as part of this project.

### Project Sponsor Tech Lead

### Collaborators

List all participants on the project. Here is a good space to share your personal goals for the hackweek and things you can help with.

| Name | Personal goals | Can help with | Role |
| ------------- | ------------- | ------------- | ------------- |
| ... | ... | ... | ... |
| ... | ... | ... | ... |
| ... | ... | ... | ... |
| ... | ... | ... | ... |

### The problem

Provide a few sentences describing the problem are you going to explore. If this is a technical exploration of software or data science methods, explain why this work is important in a broader context and specific applications of this work.

## Data and Methods

### Data

Briefly describe and provide citations for the data that will be used (size, format, how to access).

### Existing methods

How would you or others traditionally try to address this problem? Provide any relevant citations to prior work.

### Proposed methods/tools

What new approaches would you like to implement for addressing your specific question(s) or application(s)?

Will your project use machine learning methods? If so, we invite you to create a [model card](model-card.md)!

### Additional resources or background reading

Optional: links to manuscripts or technical documents providing background information, context, or other relevant information.

## Project goals and tasks

### Project goals

List the specific project goals or research questions you want to answer. Think about what outcomes or deliverables you'd like to create (e.g. a series of tutorial notebooks demonstrating how to work with a dataset, results of an anaysis to answer a science question, an example of applying a new analysis method, or a new python package).

* Goal 1
* Goal 2
* ...

### Tasks

What are the individual tasks or steps that need to be taken to achieve each of the project goals identified above? What are the skills that participants will need or will learn and practice to complete each of these tasks? Think about which tasks are dependent on prior tasks, or which tasks can be performed in parallel.

* Task 1 (all team members will learn to use GitHub)
* Task 2 (team members will use the scikit-learn python library)
  * Task 2a (assigned to team member A)
  * Task 2b (assigned to team member B)
* Task 3
* ...

## Project Results

Use this section to briefly summarize your project results. This could take the form of describing the progress your team made to answering a research question, developing a tool or tutorial, interesting things found in exploring a new dataset, lessons learned for applying a new method, personal accomplishments of each team member, or anything else the team wants to share.

You could include figures or images here, links to notebooks or code elsewhere in the repository (such as in the (shared/) folder), and information on how others can run your notebooks or code.