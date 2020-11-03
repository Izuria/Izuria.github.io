# How To Host a Resume on GitHub Pages

## Table of Contents
- [Introduction](#Introduction)
- [Prerequisites](#Prerequisites)
- [Instructions](#Instructions)
    - [Getting Started](#1-Getting-Started)
    - [Creating a Repository](#2-Creating-A-Repository)
    - [Write Resume in Markdown](#3-Write-Resume-In-Markdown)
    - [Creating an index.md file](#4-creating-an-indexmd-file)
    - [Use a Static Site Generator](#5-use-a-static-site-generator)
- [More Resources](#More-Resources)
- [Authors and Acknowledgments](#Authors-and-Acknowledgments)   
- [Frequently Asked Questions](#FAQs)


## Introduction
Have you ever wanted to host a resume on the web? An easy way to do this is through using GitHub Pages. GitHub Pages are public webpages and websites that are hosted through GitHub, for everyone to view publicly on the internet. In this tutorial, we'll go through some prerequisites, and instructions on how to host your own resume on the internet using GitHub. We will be combining Andrew Etter's book Modern Technical Writing philosophies and protocols in our instructions, explaining why we use these tools, etc.

You can view an example of a resume hosted on GitHub Pages [here](https://izuria.github.io/).


## Prerequisites

### **Required**
- Knowledge of Markdown
- A GitHub account
- A resume

### **Recommended**
 - A Markdown editor
 - Basic knowledge with Jekyll
 - Resume written in Markdown




## Instructions

### **1. Getting Started**
If you don't know any Markdown knowledge or are wanting to refresh on your Markdown skills, this [tutorial][tutorial] will help. 

Andrew Etter talks about Markdown, saying that it's an easy to learn markup language 

To begin, you want to have a GitHub account. GitHub is a code hosting website that uses a Distributed Version Control System (DVCS), where each developer can have their own repository and synchronize with each other. It helps track changes, carries metadata and maintains history for potential roll-backs to a past state. 

Andrew Etter says that DVCS have better performance compared to other VCS, allows for offline work, and are superior for concurrent work on the same file.

If you do not have a GitHub account yet, you can [click here](https://github.com/join) to redirect you to the registration page.


### **2. Creating a repository**
Once you're logged onto your GitHub account, you want to create a new repository. A repository is basically a folder hosted on GitHub, which contains all of your project's files and stores metadata relating to it. To follow the steps, go to GitHub.com, click on the "+" sign at the top right, and click new repository. From here, you **must** name your repository as _username_.github.io, where _username_ is your GitHub username. **If you don't name your repository after your username, then your page will not show up on the internet.** Once you finish creating your repository, you can visit the your GitHub page on _username_.github.io, where _username_ is your GitHub username.


### **3. Write Resume in Markdown**
At this stage, it's reccomended that you write or have your resume in Markdown. Although you can write Markdown in any text editor, using a markdown editor will help a lot and help you become more efficient with your writing. Many Markdown editors have a live preview, so you can type Markdown and see a live preview on the side. Some Markdown editors include Atom and Visual Studio Code. More text and Markdown editors can be found in [More Resources](#More-Resources).a

Here's an image of Visual Studio Code used to write Markdown with a live preview on the side.  
<img src=https://github.com/Izuria/Izuria.github.io/blob/main/images/Code_EOZkElLxBS.png width="640"/>




### **4. Creating an index.md file**
From here, you want to create an index.md file. The index.md file will be the front page of our website, and in this tutorial, will contain the content of the resume we wrote in Markdown. If you followed step 3, you should have your resume written in Markdown. From here, you can simply copy the content of your new resume and paste it into your index.md file.  

### **5. Use a static site generator**
Now that we're at this stage, we can use Jekyll. Jekyll is a static site generator that creates a theme and template for your site, and has built-in support for GitHub pages. Static site generator basically processes content and themes you give them.

![sickImage](https://github.com/Izuria/Izuria.github.io/blob/main/images/leu14xOVrS.gif)


The easiest way to use Jekyll for GitHub Pages would be by going to your repository, press the settings button, scroll to the section "GitHub Pages", and to select the theme chooser. You can choose from a preset selection of themes, and then apply it.

When doing it the easy way, you should have a _config.yml file in your repository. This is a configuation file, and documentation can be found [here][configdoc], or in more resources.

Andrew Etter says that he loves static websites, noting their speed, simplicity, portability, and security. This is true, as static websites are "static" and have a fixed content for every user, compared to dynamic websites that use Javascript or HTML5 to build different content for different users.

## More Resources
- [GitHub Pages][githubpages]
- [Markdown Tutorial][tutorial]
- [Jekyll Configuration Documentation][configdoc]
- [Andrew Etter's book][etterbook]

## Authors and Acknowledgments

Group Members
1. David Le
2. Jai Sandhu
3. Connor Hryhoruk
4. Huayi Chen


## FAQs

### **Why should we use Markdown instead of a word processor?**"  
WIP

### **"Why is my resume not showing up??"**
If your resume is not showing up, these are some potential issues:  
1. Your repository is not named after your username.
2. Your index.md is not in the main/master branch.
3. Just wait a few minutes. Sometimes your webpage hosted on GitHub Pages take a while to update.

### **"Can i change my website name/URL??"**
If you own a custom domain, you can change the default domain to one you own. [Click here](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/configuring-a-custom-domain-for-your-github-pages-site) for more details.

[etterbook]:https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS
[githubpages]:https://pages.github.com/
[tutorial]:https://www.markdowntutorial.com/
[configdoc]:https://jekyllrb.com/docs/configuration/
