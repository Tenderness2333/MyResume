How to post a resume on a website
=================================


## Purpose

This README teaches anyone how to post a resume on a website using Jekyll and Markdown. If you have limited technical experience, don't worry. This README covers version control, static website and Markdown, and relates each step to the key principles from *Modern Technical Writing* by Andrew Etter. It is intended for readers who have no experience with Git, static site generators or forges.



## Prerequisites
* A Markdown resume
* [VS Code](https://code.visualstudio.com)
* A [GitHub](https://github.com) account
* Some basic knowledge about Markdown
* [Git](https://git-scm.com/)


## Instructions

1. Create a new repository on GitHub. Click the "+" button on the top-right corner of the home page and select "New repository"
2. Open PowerShell on your computer
3. Create a new folder in your computer, and use powershell to find your folder,type the following command:

```bash
cd yourfolder
```
4. Initialize your git, type the following command:
```bash
git init
```
5. Connect the github repository, type the following command:
```bash 
git remote add origin https://github.com/yourusername/yourrepository.git
```
6. If this is your first time to use git, type the following command:
```bash
git config --global user.name "anything you like"
git config --global user.email "your email"
```
7. Add the file to the git, type the following command:
```bash
git add .
```
8. Commit your file
```bash
git commit -m "first commit"
```
9. Make sure the branch is main
```bash
git branch -M main
```
10. Push the file to GitHub
```bash
git push -u origin main
```
11. Click the Settings on GitHub, and find the Pages on left side

12. Change the Branch to main from None, and click the save button

13. remember the link from that page (e.g. https://username.github.io/Resume/)

## Further readings

* [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) by Andrew Etter

* [Markdown Guide](https://www.markdownguide.org/)

* [Make a README](https://www.makeareadme.com/)
* [Jekyll](https://jekyllrb.com/)

## FAQ

What is Jekyll?
* Jekyll is a tool to help you build the website. You can add a new file on your GitHub, The name of this file must be _config.yml, you can add some feature in it, something like 
```bash
title: your title
remote_theme: pages-themes/midnight@v0.2.0
```

Why do we need version control?
* We need version control becasue sometimes , we have many ideas or we work with other people. After we try some way to code, we want to rollback or we need to try other way to do it, so we need branch.

Why do we use Markdown to write our resume?
* We use Markdown becasue Markdown is easy to convert to the HTML language. If we use HTML, it is hard to do that. And markdown language is easy to use. 

What if I get problems from Git?
* Git is hard to understand for first time, but you can esay to find the tutirial from website.

## Credits

Special thanks to
* Sage Stoddart
* Dat Nguyen
