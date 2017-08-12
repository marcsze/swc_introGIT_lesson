# Intro to GitHub Lesson Plan
**Originally designed for a SWC session from August 17th - August 18th**

### Preamble

This repository contains all the material needed as well as a description and walkthrough of all the different topics that will be covered during the session.

### Obtaining Example Data Set

There shouldn't be any need to get data since it will all be generated during the lesson. 

### Automated Version Control

* The information for this lesson can be found [here](https://swcarpentry.github.io/git-novice/01-basics/). 

* Main Question
  * Imagine you drafted an excellent paragraph for a paper you are writing, but later ruin it. How would you retrieve the excellent version of your conclusion? Is it even possible? Imagine you have 5 co-authors. How would you manage the changes and comments they make to your paper? If you use LibreOffice Writer or Microsoft Word, what happens if you accept changes made using the Track Changes option? Do you have a history of those changes?

* At the end of the lesson (after the question) can show an example of version control with the following [repo for obesity](https://github.com/SchlossLab/Sze_Obesity_mBio_2016/commits/master). This will help to illustrate what it looks like in real life before we delve into the example problems and getting used to using the system.


### Setting up Git

* First should take them to the [main website](https://github.com/) so that they can create their own account.

* Before everything gets started need to make sure that everyone has Git installed on their computers.
  * type in `which git` onto their command line
    * If there is a response with a path e.g. `/usr/bin/git` then things should be okay to proceed

* The specific lesson can be found [here](https://swcarpentry.github.io/git-novice/02-setup/)
  * Need to emphasize that the username should be the one they used to create the online Git account
  * Should also state that if you are not comfortable with vim you should change the default editor.


### Creating a Repository

* The learners can choose where they would like to work but need to emphasize that it is important they have the directory created
  * Stress that everything will be relative to this directory `planets`
  
* The specific lesson can be found [here](https://swcarpentry.github.io/git-novice/03-create/)
  * For the question might be best to ignore the component on `.gitignore` for now. 


### Tracking Changes

* Can use the provided example to pictorially describe what `git add` and `git commit` are doing
  * ![example_overview](https://swcarpentry.github.io/git-novice/fig/git-committing.svg)
  
  * can highlight this is like a last chance to undo things you are unhappy with before permantely commiting to it.
  
* Make sure to go over the yellow tabs as they are samll scale but important. Based on the level of the class might be able to ignore "paging the log" and "limit log size". Should definitely go over "word-based diffing" and "directories"

* By the end if time is permitting should go over all the questions to make sure that the concepts have stuck. Can ignore the final question on "Author and Committer" 

* The lesson can be found [here](https://swcarpentry.github.io/git-novice/04-changes/)



  

