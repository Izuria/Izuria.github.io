# How To Host a Resume on GitHub Pages

## Table of Contents
- [Introduction](#Introduction)
- [Prerequisites](#Prerequisites)
- [Instructions](#Instructions)
    - [Getting Started](#1-Getting-Started)
    - [Creating a Repository](#2-Creating-A-Repository)
    - [Creating an index.md file](#3-creating-an-indexmd-file)
    - [Use a Static Site Generator](#4-use-a-static-site-generator)
- [More Resources](#More-Resources)
- [Authors and Acknowledgments](#Authors-and-Acknowledgments)   
- [Frequently Asked Questions](#FAQs)


## Introduction
Have you ever wanted to host a resume on the web? An easy way to do this is through using GitHub Pages. GitHub Pages are public webpages and websites that are hosted through GitHub, for everyone to view publicly on the internet. In this tutorial, we'll go through some prerequisites, and instructions on how to host your own resume on the internet using GitHub. We will be combining Andrew Etter's book Modern Technical Writing philosophies and protocols in our instructions to help explain why these concepts and instructions are good.

You can view an example of a resume hosted on GitHub Pages [here](https://izuria.github.io/).


## Prerequisites

### **Required**
- Knowledge of Markdown
- A GitHub account
- A resume written in Markdown

### **Recommended**
 - A Markdown editor
 - Basic knowledge with Jekyll

## Instructions

### **1. Getting Started**
If you don't know any Markdown knowledge or are wanting to refresh on your Markdown skills, this [tutorial][tutorial] will help. 

> Andrew Etter talks about Markdown, saying that it's the most popular markup language that is easy to learn and has the cleanest syntax. We're able to use this Markdown many different ways, such as writing documentation, or in our case, a resume.

It's highly recommended that you use a text editor that supports Markdown, or just use a Markdown editor. Markdown editors will help a lot and help you become more efficient with your writing. Many Markdown editors have a live preview, so you can type Markdown and see a live preview on the side. Some text/Markdown editors include [MarkdownPad](http://markdownpad.com/) and [Visual Studio Code](https://code.visualstudio.com/). More text and Markdown editors can be found in [More Resources](#More-Resources).

Here's an image of Visual Studio Code used to write Markdown with live preview.  
<img src=https://github.com/Izuria/Izuria.github.io/blob/main/images/Code_EOZkElLxBS.png width="640"/>

To begin, you want to have a GitHub account. GitHub is a code hosting website that uses a Distributed Version Control System (DVCS), where each developer can have their own repository and synchronize with each other. It helps track changes, carries metadata and maintains history for potential roll-backs to a past state. 

> Andrew Etter says that DVCS have better performance compared to other VCS, allows for offline work, and is superior for concurrent work on the same file. 

If you do not have a GitHub account yet, you can [click here](https://github.com/join) to redirect you to the registration page.


### **2. Creating a repository**
Once you're logged onto your GitHub account, you want to create a new repository. A repository is basically a folder hosted on GitHub, which contains all of your project's files and stores metadata relating to it. 

To create a new repository for GitHub Pages:
1. On GitHub.com, click on the "+" sign at the top right, and then press new repository.
2. Name your repository as _username_.github.io, where _username_ is your GitHub username. **If you don't name your repository after your username, then your page will not show up on the internet.**

Once you finish creating your repository, you can visit the your GitHub page on _username_.github.io, where _username_ is your GitHub username.


### **3. Creating an index.md file**
From here, you want to create an index.md file. The index.md file will be the front page of our website, and in this tutorial, will contain the content of the resume we wrote in Markdown. From here, if you want your front page to be your resume, you can simply copy the content of your new resume and paste it into your index.md file.

### **4. Use a static site generator**
Now that we're at this stage, we can use Jekyll. Jekyll is a static site generator that creates a theme and template for your site, and has built-in support for GitHub pages. Static site generator basically processes the data (Markdown) and a theme of your choosing and fills out the template for you.

The easiest way to use Jekyll for GitHub Pages would be:
1. Go to your repository and press settings.
2. Scroll to the section "GitHub Pages", and to select the theme chooser. 
3. Choose from a preset selection of themes, and then apply it.


Here's a GIF to follow the steps   
![sickImage](https://github.com/Izuria/Izuria.github.io/blob/main/images/leu14xOVrS.gif)

When doing it this way, a _config.yml file should be generated in your repository. This is a configuation file, and documentation can be found [here][configdoc], or in more resources. Edit your _config.yml and add these lines.
```yml
title: <your name> Resume
```

Once finished, visit your GitHub pages website at _username_.github.io and check out your resume!

> Andrew Etter advocates for static websites, noting their speed, simplicity, portability, and security. They have no dependencies, generally no databases, and nothing to install. I agree with Etter, in which their speed, simplicity, and security make it great, as static websites are "static" and have fixed content for every user, compared to dynamic websites that use Javascript or HTML5 to build different content for different users.



## More Resources
- [GitHub Pages][githubpages]
- [Markdown Tutorial][tutorial]
- [Jekyll Configuration Documentation][configdoc]
- [Andrew Etter - Modern Technical Writing: An Introduction to Software Documentation][etterbook]
- [Markdown Editors](https://www.oberlo.ca/blog/markdown-editors)

## Authors and Acknowledgments

[Andrew Etter](https://andyetter.com/) for his book: Modern Technical Writing: An Introduction to Software Documentation.

Group Members
1. David Le
2. [Jai Sandhu](https://github.com/jai-sandhu/jai-sandhu.github.io)
3. [Connor Hryhoruk](https://github.com/h-connor/h-connor.github.io)
4. [Huayi Chen](https://github.com/ChenHuayi131/ChenHuayi131.github.io)


## FAQs

### **Why should we use Markdown instead of a word processor?**"  
It really depends on what you're trying to accomplish. While a word processor can make for great _traditional_ resumes, a resume in Markdown can be used in many places. Markdown should be used for material such as documentation, READMEs, or for progressive resumes to host online, as it will be more efficient than using a word processor.

### **"Why is my resume not showing up?"**
If your resume is not showing up, these are some potential issues:  
1. Your repository is not named after your _username_.github.io.
2. Your index.md is not in the main/master branch.
3. Just wait a few minutes. Sometimes webpage hosted on GitHub Pages take a while to update.

### **"Can i change my website name/URL?"**
If you own a custom domain, you can change the default domain to one you own. [Click here](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/configuring-a-custom-domain-for-your-github-pages-site) for more details.

[etterbook]:https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS
[githubpages]:https://pages.github.com/
[tutorial]:https://www.markdowntutorial.com/
[configdoc]:https://jekyllrb.com/docs/configuration/
# How To Host a Resume on GitHub Pages

## Table of Contents
- [Introduction](#Introduction)
- [Prerequisites](#Prerequisites)
- [Instructions](#Instructions)
    - [Getting Started](#1-Getting-Started)
    - [Creating a Repository](#2-Creating-A-Repository)
    - [Creating an index.md file](#3-creating-an-indexmd-file)
    - [Use a Static Site Generator](#4-use-a-static-site-generator)
- [More Resources](#More-Resources)
- [Authors and Acknowledgments](#Authors-and-Acknowledgments)   
- [Frequently Asked Questions](#FAQs)


## Introduction
Have you ever wanted to host a resume on the web? An easy way to do this is through using GitHub Pages. GitHub Pages are public webpages and websites that are hosted through GitHub, for everyone to view publicly on the internet. In this tutorial, we'll go through some prerequisites, and instructions on how to host your own resume on the internet using GitHub. We will be combining Andrew Etter's book Modern Technical Writing philosophies and protocols in our instructions to help explain why these concepts and instructions are good.

You can view an example of a resume hosted on GitHub Pages [here](https://izuria.github.io/).


## Prerequisites

### **Required**
- Knowledge of Markdown
- A GitHub account
- A resume written in Markdown

### **Recommended**
 - A Markdown editor
 - Basic knowledge with Jekyll

## Instructions

### **1. Getting Started**
If you don't know any Markdown knowledge or are wanting to refresh on your Markdown skills, this [tutorial][tutorial] will help. 

> Andrew Etter talks about Markdown, saying that it's the most popular markup language that is easy to learn and has the cleanest syntax. We're able to use this Markdown many different ways, such as writing documentation, or in our case, a resume.

It's highly recommended that you use a text editor that supports Markdown, or just use a Markdown editor. Markdown editors will help a lot and help you become more efficient with your writing. Many Markdown editors have a live preview, so you can type Markdown and see a live preview on the side. Some text/Markdown editors include [MarkdownPad](http://markdownpad.com/) and [Visual Studio Code](https://code.visualstudio.com/). More text and Markdown editors can be found in [More Resources](#More-Resources).

Here's an image of Visual Studio Code used to write Markdown with live preview.  
<img src=https://github.com/Izuria/Izuria.github.io/blob/main/images/Code_EOZkElLxBS.png width="640"/>

To begin, you want to have a GitHub account. GitHub is a code hosting website that uses a Distributed Version Control System (DVCS), where each developer can have their own repository and synchronize with each other. It helps track changes, carries metadata and maintains history for potential roll-backs to a past state. 

> Andrew Etter says that DVCS have better performance compared to other VCS, allows for offline work, and is superior for concurrent work on the same file. 

If you do not have a GitHub account yet, you can [click here](https://github.com/join) to redirect you to the registration page.


### **2. Creating a repository**
Once you're logged onto your GitHub account, you want to create a new repository. A repository is basically a folder hosted on GitHub, which contains all of your project's files and stores metadata relating to it. 

To create a new repository for GitHub Pages:
1. On GitHub.com, click on the "+" sign at the top right, and then press new repository.
2. Name your repository as _username_.github.io, where _username_ is your GitHub username. **If you don't name your repository after your username, then your page will not show up on the internet.**

Once you finish creating your repository, you can visit the your GitHub page on _username_.github.io, where _username_ is your GitHub username.


### **3. Creating an index.md file**
From here, you want to create an index.md file. The index.md file will be the front page of our website, and in this tutorial, will contain the content of the resume we wrote in Markdown. From here, if you want your front page to be your resume, you can simply copy the content of your new resume and paste it into your index.md file.

### **4. Use a static site generator**
Now that we're at this stage, we can use Jekyll. Jekyll is a static site generator that creates a theme and template for your site, and has built-in support for GitHub pages. Static site generator basically processes the data (Markdown) and a theme of your choosing and fills out the template for you.

The easiest way to use Jekyll for GitHub Pages would be:
1. Go to your repository and press settings.
2. Scroll to the section "GitHub Pages", and to select the theme chooser. 
3. Choose from a preset selection of themes, and then apply it.


Here's a GIF to follow the steps   
![sickImage](https://github.com/Izuria/Izuria.github.io/blob/main/images/leu14xOVrS.gif)

When doing it this way, a _config.yml file should be generated in your repository. This is a configuation file, and documentation can be found [here][configdoc], or in more resources. Edit your _config.yml and add these lines.
```yml
title: <your name> Resume
```

Once finished, visit your GitHub pages website at _username_.github.io and check out your resume!

> Andrew Etter advocates for static websites, noting their speed, simplicity, portability, and security. They have no dependencies, generally no databases, and nothing to install. I agree with Etter, in which their speed, simplicity, and security make it great, as static websites are "static" and have fixed content for every user, compared to dynamic websites that use Javascript or HTML5 to build different content for different users.



## More Resources
- [GitHub Pages][githubpages]
- [Markdown Tutorial][tutorial]
- [Jekyll Configuration Documentation][configdoc]
- [Andrew Etter - Modern Technical Writing: An Introduction to Software Documentation][etterbook]
- [Markdown Editors](https://www.oberlo.ca/blog/markdown-editors)

## Authors and Acknowledgments

[Andrew Etter](https://andyetter.com/) for his book: Modern Technical Writing: An Introduction to Software Documentation.

Group Members
1. David Le
2. [Jai Sandhu](https://github.com/jai-sandhu/jai-sandhu.github.io)
3. [Connor Hryhoruk](https://github.com/h-connor/h-connor.github.io)
4. [Huayi Chen](https://github.com/ChenHuayi131/ChenHuayi131.github.io)


## FAQs

### **Why should we use Markdown instead of a word processor?**"  
It really depends on what you're trying to accomplish. While a word processor can make for great _traditional_ resumes, a resume in Markdown can be used in many places. Markdown should be used for material such as documentation, READMEs, or for progressive resumes to host online, as it will be more efficient than using a word processor.

### **"Why is my resume not showing up?"**
If your resume is not showing up, these are some potential issues:  
1. Your repository is not named after your _username_.github.io.
2. Your index.md is not in the main/master branch.
3. Just wait a few minutes. Sometimes webpage hosted on GitHub Pages take a while to update.

### **"Can i change my website name/URL?"**
If you own a custom domain, you can change the default domain to one you own. [Click here](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/configuring-a-custom-domain-for-your-github-pages-site) for more details.

[etterbook]:https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS
[githubpages]:https://pages.github.com/
[tutorial]:https://www.markdowntutorial.com/
[configdoc]:https://jekyllrb.com/docs/configuration/
