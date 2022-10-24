---
title: "README"
author: "jsg"
date: "Last compiled on 25 August, 2022 12:19"
output:
  html_document:
    toc: true
    toc_float: true
    keep_md: true
    self_contained: true
---

This repository holds all the files we'll use to introduce you to data science 
and it's related tools (R, Rstudio, git).  

### Required tools

* **Get access to R!**. You can make an account at Rstudio cloud (https://rstudio.cloud/).
You can also install R (https://cran.r-project.org/) and Rstudio (https://www.rstudio.com/) 
on your machine, but I **strongly recommend** starting with Rstudio cloud.  
Rstudio cloud is free for up to 50 hours/month, you don't have to maintain it, and
it gives gives a standard install (same on all machines, so your intro/
our training may be smother).  You can also do both.  If you need help, 
videos are at :
  * [Downloading R](https://www.youtube.com/watch?v=S8GrH0MeWkM&list=PLmnVhyQ-20EUFRmsjpYTyB5--zyolr6-o&index=2){target="_blank"}
  * [Downloading Rstudio](https://www.youtube.com/watch?v=pklpCOmK9Cg&list=PLmnVhyQ-20EUFRmsjpYTyB5--zyolr6-o&index=3){target="_blank"}
  * [Making a Rstudio cloud account](https://www.youtube.com/watch?v=ojqNuBRR0y0&list=PLmnVhyQ-20EUFRmsjpYTyB5--zyolr6-o&index=5){target="_blank"}
* Join the github classroom we'll be using for our sessions
  * Check blackboard for your class!
  * When you visit the page it will ask you to connect or create a github 
  repository. You can use 
any name (be anonymous or not) that you want.  This is a free process.

### Getting started on an assignment

It may be easier to open these instructions in a browser so you can follow along
there while working in Rstudio!

At this point I’m assuming you received an invitation to view an assignment on
github classroom and accepted it.After you join the github classroom, you'll make 
a clone of the repository onto your
machine.  First, find your copy of the repository. You can follow the github 
classroom link again, or log into github and then visit 
https://github.com/settings/repositories. Find the repository called
data_science_intro_YOURGITHUBUSERNAME, and click on it. Then follow along below -
find instructions for Rstudio cloud or Rstudio desktop depending on your setup.

#### If you are using Rstudio cloud...

Video at [Accepting your first github repository (from github classroom) and cloning to
**Rstudio cloud**](https://www.youtube.com/watch?v=GzQ6Dsze8qo&list=PLmnVhyQ-20EUFRmsjpYTyB5--zyolr6-o&index=6){target="_blank"}

Log into your [Rstudio cloud account](https://rstudio.cloud/){target="_blank"}.
You'll see something like this:

![Rstudio cloud home screen](https://lh3.googleusercontent.com/pw/ACtC-3dVAm8XnMQH9ebnayG0SgBgSewlPFWyJmubIbASefCQ0NKiuZHsQO6eUbzy-Y0LZ6U7KbPkmHCi91tJ4lm7xPs4xf0A3fyMXyMKuzfJ6B2tADIq_NX9GmYRrZS5OuZ6Y1DcCxyzMmmEsV-_DyV9XrLLJA=w1320-h581-no?authuser=0)

To copy a repository, select **New Project**, **New Project from Github repo**.
Next you’ll need to enter the url for your repository. To find this, click on the
Code button from the github page for your repository 
([instructions above!](### Optional (get a head start if you want)
))

![Click on Code to get repository url](https://lh3.googleusercontent.com/pw/ACtC-3c6iXUxY_YkEQktN9szfL0Jfl3-jJnjfp2dwbMU_NtnOtoCOFzJcpRN1r0X0zCZlH2gtB9JlXz7_WLgXMBAU7a2K_vwTX5taNBBWwSgsO558aqLZEtKmH_cMpwv7ukzYi7R4ffncWbcscAy8sAzBcZ4Ww=w692-h490-no?authuser=0)

Copy the 
web url (or click the copy icon). Input that into the field asking for the URL
of your github repository. 

Note you may need to enter your github username and password to create the repository.

Before continuing,  I recommend turning down the computer usage. Free rstudiocloud 
accounts only allow so much usage, but that depends on how much power you allocate
to a project. To do this, click on the RAM icon in the upper left corner, select 
resources, and move all sliders to the far left.

![In Rstudio cloud, move all sliders to the left to give you more actual hours](https://lh3.googleusercontent.com/pw/AM-JKLVGtN01ndQcB622ioe8eLk0vcbTgdlE2QXG8L_q0scnCBEXjhn4Kvik3Lqm7BoiI11p0YaTYq5NlWaXa303IVly68oNYqfJoQWoNWnAyWUyo5fRcrQ39lrvFBdWP1J-qGd84xGNFN-U1aGgfF5ac6FsAA=w329-h734-no?authuser=0)

If you end up doing something more complex, you can increase allocated power to 
speed everything up. For most class code, however, low power should be fine.)  If
you make changes here, Rstudio.cloud will need to relaunch to apply them. Let it do
that then keep working.

The next screen will bring you to a "normal" RStudio screen.  Continue to the 
[**Now we can actually work in R**](## Now we can actually work in R and markdown) 
section to get started


#### If you are using RStudio on your desktop (or via a server...anywhere that 
looks like an RStudio screen)

Video at [Accepting your first github repository (from github classroom) and cloning to
**Rstudio desktop**](https://www.youtube.com/watch?v=AjrcY0eB54U&list=PLmnVhyQ-20EUFRmsjpYTyB5--zyolr6-o&index=7&t=453s){target="_blank"}

To start working on an assignment, open RStudio. 

![Select File > New Project in Rstudio](https://lh3.googleusercontent.com/pw/ACtC-3ddyHNvzmRICUa_CmWQmzbz5jr9aTdo_bs9yH9ZbfUPe2LjS46TYj1FsD7CjhKL3rknFZkui-YecWokRGY03cj8occR5HJN56P5N8KJTCUPgciKCAwD8YHJEKXXOOjH-LI8k1G8p88MGB7d_6ov4EJtQQ=w879-h664-no)

Select file, new project, Version control. On the next screen select git. If this
isn't available, you may need to install git (free) on your system.  You can 
download it at https://git-scm.com/download/.  

Next you’ll need to enter the url for your repository. To find this, click on the
Code button from the github page for your repository 
([instructions above!](### Optional (get a head start if you want)
)).

![Click on Code to get repository url](https://lh3.googleusercontent.com/pw/ACtC-3c6iXUxY_YkEQktN9szfL0Jfl3-jJnjfp2dwbMU_NtnOtoCOFzJcpRN1r0X0zCZlH2gtB9JlXz7_WLgXMBAU7a2K_vwTX5taNBBWwSgsO558aqLZEtKmH_cMpwv7ukzYi7R4ffncWbcscAy8sAzBcZ4Ww=w692-h490-no?authuser=0)

Copy the web url (or click the copy icon). Input that into the Rstudio Repository URL 
space. You can select/edit what you want the repository to be called and where its 
stored (its just a folder on your computer). For example, I have a Repositories folder in my 
main hard drive where I save all of these.  Then select Create project. 
Whatever you choose, the project will be saved in new folder in that location 
using the name you chose. Note you may need to enter your github username and password to create the repository. 

**You also may get an error/warning about personal access token!** this happens
at different points on different machines (thus why Rstudio cloud is nice).  If
 you see this now, see [below](### Github 2-factor authentication (required as of Fall 2021)) 
 for help.  
 
If everything work, the next screen will bring you to a "normal" RStudio screen.  
Continue to the 
[**Now we can actually work in R**](## Now we can actually work in R and markdown) 
section to get started


#### Now we can actually work in R and markdown

Now you can start working on the files in the repository in
Rstudio.  To view the files, make sure 
you are in the right repository.  You should see whatever you named the project in the
upper right hand corner of Rstudio. If you don't go to File > Open Project and 
navigate to where you placed the repository.  

Once you are in the right project, open the file you want to work on.   From 
inside the project space, go to **File**, **Open File**
and find it, or look in the Files window to find and open the file. 

For example, our first assignment is in the 1._Getting_used_to_R folder. We'll
work through the 1_intro_to_R.R script first. Open the file, and a window with a lot of text should 
appear in your Rstudio. 

#### Editing, committing, and pushing changes

To understand how git works, change line 2 of the 1_intro_to_R.R file
to have your name.  Then hit save (disk icon).  This saves a copy of the file 
on your machine.  In order for me to see it, we need to push those changes to a github
repository.  

#### Committing files to your github repository

If you look in the upper right windows, you should see a *Git* tab.  Select it. 

![The git tab allows you to use git commands in Rstudio](https://lh3.googleusercontent.com/pw/ACtC-3cew_BrIh1yE8pXRHanoR8pkhTqwPig8u0_jAgldEbZ2mBpE87uUsToH9HYvOsCCCYYJAfY1vVVAOW5evyBIW7NHpWxiS60QZH-2dM9WZnp96r9x3JcBejVWqRxR7tQP81WuDxzk5nRyzLVWDfRD86fiA=w533-h108-no)

Notice it has several files. These are the files you have changed or created 
since you started working.  Click the checkbox next to the files, and select
**Commit**.  You'll need to enter a description. Put "My first commit!" and
press Commit.  

If you get a screen that looks like this:

![This screen means you need to tell your computer who to assign changes to](https://lh3.googleusercontent.com/pw/ACtC-3eiPjAQ9iNeBsac3EtLzSqZm1UEen9Apc1HAn7mV6NueYqAlkDGl8AgeBD0_gV21CySVxP5AaQIQDNJYhiAVhN8pqx6eUSIH69DWSQn2-eMMx-802NaxjcJ62pLHMMR2Enin-b2Ex4gb9D88jrQTYEW0w=w749-h331-no?authuser=0)

It just means we need to associate an identity with the commits. To do this,
close (x) the git windows. Select the terminal tab:

![The terminal tab lets you send commands to your computer](https://lh3.googleusercontent.com/pw/ACtC-3dm7BlCVoK7RYCQS-sB66LWveip4Hude5tmpeALZEMJm_nR1AKVP_R-1SON-7JrvBPNZb28HWBFax2SqRCtf1iJNNUXBrTg6UupRMJhRPZIGWHy1a3QXgQYlwipDxyg0T6K4I7Q5jTVwamUfwgSBfBcpQ=w462-h228-no?authuser=0)

Then paste this line into the terminal (tab to the right of the console tab), 
(note you need 2 -- should be 2
dashes!)

git config --global user.email "you@example.com"

replace the email with your email (leave the quotes) and press enter.

Then paste this line into the terminal, 

git config --global user.name "Your Name"

replace the Your Name with your name (leave the quotes) and press enter. 

Now go back to the git window and try the commit again. It should work. You will
only have to do this once (for desktop versions) and only occasionally for 
cloud-based RStudio instances.

Now you've *committed* to the file to your local Rstudio instance (on
your own machine or server), which is itself a git repository.  This is different 
than a save. A save overwites the current file, while a commit compares changes you
have made and tracks them. To see this, you can go the **Git** tab, select **Diff**, and
then **History** on the pop-you.  From there, you can select the commit, select 
any file you committed, and actually see the
changes.  This allows you to go back to (or just see) earlier versions easily, which is often helpful
in programming.  

#### Pushing to github

Now you need to push these changes to the cloud so I can see them (or, in the 
future, so you could share with collaborators or save a copy for yourself).
From the **Git** tab, select **Push**. As of Fall 2021, Github no longer accepts usernames and
passwords for authentication.  However, Rstudio may ask you for these depending on
what version you are using.  Don't be surprised if you enter your password correctly
but your attempt to create a 
repository (or push commits to it) still fails because you need to setup or reset a
token.  

![If you see this, it means you need to setup or reauthorize a github token](https://lh3.googleusercontent.com/pw/AM-JKLW24QFJWE5drC-dx2ldqcUZtNvtC-zl6HIiQLUoRYcy9enZV1eomlHk3afwzU_uiythMdAZlKi2eY_nlmdBgpcWcxK5qcZWPnufblrmUYb2bB4YOqBpEQaRqRpQWEX86lRACZFIe2OjFmZYwT30_fYjxA=w704-h296-no?authuser=0)

If you see this message now, go to the 
**Github 2-factor authentication (required as of Fall 2021)** section!). If not,
you can continue, but note you'll have to do it later (when you push changes).

#### Github 2-factor authentication (required as of Fall 2021)

Github requires you to use a token to verify you have permission to make changes 
to repositoties that you store there.  To create a token, can use the code below.
If this file is open in R, you can select the green triangle button (play
icon) to run the current chunk. Otherwise you can copy and paste it into R. 
Note you may also need to install the usethis library first.


```r
library(usethis)
usethis::create_github_token()
```

This will launch a browser pointed to github. You may need to log in. Then it will
have you name a PAT (personal access token). You can, for example, name it Rstudio.
Then scroll to the bottom, and select **Generate Token**. Save the token somewhere 
(you'll never see it again once you close the window).  Then run the next code 
chunk.  Select 3, then paste in the 
token you just generated. Again, you may need to install the gitcreds package.


```r
library(gitcreds)
gitcreds_set()
```

This process is letting your computer and github communicate and should only need 
to be done once for a desktop.  For rstudio.cloud, you will need to regularly reenter 
the token, but you don't have to recreate it. *So save you PAT somewhere just in case*. 
If/when you lose it, however, you can simply make a new one and reconnect the 
repositories.  

Once you enter your git credentials, try to push your changes again. It should 
work this time. A window should appear. When it's done
(white text shows) go to your github repository (on the web). Open the folder for this 
assignment and click on the .md file.  It should preview, and you should see the 
updated file with your name!  Congratulations!

As you work, use commits to save snapshots of your work in a version control manner, 
and 
pushes to share them.  If you get stuck, you can also push your file up
so I can see it and help you fix it (much better than "My code isn't working). 
Then you can actually see "how" I fixed it.  The code will also be useful for 
assessments.

### Extra resources

* Easy (but no longer updated) intro to R
  * [YaRrr! The Pirate's Guide to R](https://bookdown.org/ndphillips/YaRrr/)
  * This is produced using rmarkdown!
* My stat class
  * https://sites.google.com/view/biostats/home
  * swirl (R tutorials), books, etc

[comment]:(This is an comment in Rmarkdown. It won't be seen the processed file. I
use these to leave notes that you can ignore.  
ADD HERE IF YOU CAN @TEACHER IN COMMIT FOR HELP!)


Need help? Contact me (stephen.gosnell@baruch.cuny.edu):

