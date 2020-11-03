# How To Host a Resume on GitHub Pages

TWO GOALS IN THIS README
1. how to host resume on github
2. relate steps to andrew etter

## Table of Contents

- [Introduction](##Introduction)
- [Prerequisites](##Prerequisites)
- [Instructions](##Instructions)
    - [Getting Started](###1.-Getting-Started)
    - [Creating a Repository](###2.-Creating-A-Repository)
    - [Write Resume in Markdown](###3.-Write-Resume-In-Markdown)
    - [Creating an index.md file](###4.-creating-an-index.md-file)
    - [Use a Static Site Generator](###5.-use-a-static-site-generator)
- [More Resources](##More-Resources)
- [Authors and Acknowledgments](##Authors-and-Acknowledgments)
- [Frequently Asked Questions](##FAQs)


## Introduction

Have you ever wanted to host a resume on the web? An easy way to do this is through using GitHub pages. GitHub Pages are public webpages and websites that are hosted through GitHub, for everyone to view publicly on the internet. In this tutorial, we'll go through some prerequisites, and instructions on how to host your own resume on the internet using GitHub. We will be combining Andrew Etter's book Modern Technical Writing in our instructions, explaining why we use these tools, etc.


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
If you don't know any Markdown knowledge or are wanting to refresh on your Markdown skills, this [tutorial][tutorial] will help. Andrew Etter

To begin, you want to have a GitHub account. If you do not have an account yet, you can click here to redirect you to the registration page.


### **2. Creating a repository**
Once you're logged onto your GitHub account, you want to create a new repository. On the website, click on the "+" sign at the top right, and click new repository. From here, you **must** name your repository as _username_.github.io, where _username_ is your GitHub username. **If you don't name your repository after your username, then your page will not show up on the internet.** Once you finish creating your repository, you can visit the your GitHub page on _username_.github.io, where _username_ is your GitHub username.


### **3. Write Resume in Markdown**
At this stage, it's reccomended that you write or have your resume in Markdown. Although you can write Markdown in any text editor, using a markdown editor will help a lot and help you become more efficient with your writing. Many Markdown editors have a live preview, so you can type Markdown and see a live preview on the side. Some Markdown editors include Atom and Visual Studio Code. More text and Markdown editors can be found in [More Resources](##More-Resources).

<img src="https://github.com/Izuria/Izuria.github.io/blob/main/images/Code_EOZkElLxBS.png" width="640">




### **4. Creating an index.md file**
From here, you want to create an index.md file. The index.md file will be the front page of our website, and in this example, will contain the content of the resume we wrote in Markdown. If you followed step 3, you should have your resume written in Markdown. From here, you can simply copy the content of your new resume and paste it into your index.md file.


### **5. Use a static site generator**
At this stage, we can use Jekyll. Jekyll is a static site generator that creates a theme and template for your site, and has built-in support for GitHub pages. 

The easiest way to use Jekyll for GitHub Pages would be by going to your repository, press the settings button, scroll to the section "GitHub Pages", and to select the theme chooser. You can choose from a preset selection of themes, and then apply it.

When doing it the easy way, you should have a _config.yml file in your repository. This is a configuation file, and documentation can be found [here][configdoc], or in more resources.

## More Resources

- [GitHub Pages][githubpages]
- [Markdown Tutorial][tutorial]
- [Jekyll Configuration Documentation][configdoc]
- LINK

## Authors and Acknowledgments



## FAQs


### **Why should we use Markdown instead of a word processor?**"  
---

WELL JIMMY, using a word  prcessor

### **"Why is my resume not showing up??"**
---

### **"Can i change my website name/URL??"**
---
WELL JIMMY, 

[githubpages]:https://pages.github.com/
[tutorial]:https://www.markdowntutorial.com/
[configdoc]:https://jekyllrb.com/docs/configuration/
