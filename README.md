How to post a resume on a website
=================================


## Purpose

This README teaches readers with basic Markdown knowledge how to post a resume on a website using Jekyll and Markdown. This README covers version control, static websites and Markdown, and relates each step to the key principles from *Modern Technical Writing* by Andrew Etter. Don't worry if you are new to Git or static site generators.



## Prerequisites
* A Markdown resume
* You can download VS Code [here](https://code.visualstudio.com)
* You can register GitHub [here](https://github.com)
* Some basic knowledge about Markdown
* You can download Git [here](https://git-scm.com/)


## Instructions
### Use Lightweight Markup

Etter recommends using a lightweight markup language which has clean syntax. Markdown is human-readable and easy to learn. Markdown works well with static site generators because it can be easily converted to HTML. Markdown is easy for most people, so it makes it easy to work with others.

1. Open VS Code (or another text editor).
2. Create a new file called `resume.md`.
3. Write your resume using Markdown syntax.
4. Save the file.

### Use Distributed Version Control
Etter also recommends using a distributed version control system like Git to manage documentation. Distributed version control system can help developers collaborate with others while keeping content consistent. It also tracks changes and history of the project. Developers can work on their projects offline and then push their changes to a remote repository when they are ready.

5. Open PowerShell on your computer.
6. Configure your Git username by typing the following command:
```bash
git config --global user.name "your name"
```
7. Configure your Git email by typing the following command:
```bash
git config --global user.email "your email"
```
8. Create a new folder for your project on your computer.

9. Navigate to the folder by typing the following command:
```bash
cd path/yourfolder
```

10. Initialize your Git repository by typing the following command:
```bash
git init
```

11. Click the "+" button on the top-right corner of the home page.

12. Select "New repository".

13. Enter a repository name.
14. Click the **"Create repository"**.
15. Copy the repository URL.

16. Link your local repository to GitHub repository by typing the following command:
```bash 
git remote add origin https://github.com/yourusername/yourrepository.git
```
17. Add the file to Git by typing the following command:
```bash
git add .
```
18. Commit your file by typing the following command:
```bash
git commit -m "first commit"
```
19. Set your default branch to main by typing the following command:
```bash
git branch -M main
```
20. Push the file to GitHub by typing the following command:
```bash
git push -u origin main
```

### Make Static Websites

Etter recommends using static websites, because they are fast, simple, portable, and secure. It is easy to host static websites anywhere including GitHub. We do not need to maintain the website constantly, because it is static pages. Otherwise we would need to deal with XML and database. Jekyll is a good tool to help you build static websites. GitHub Pages natively supports Jekyll, so you do not need to install it locally.

21. Create a new file called `_config.yml` in the same folder as your resume.

22. Add the following content:
```yaml
title: your title
remote_theme: pages-themes/midnight@v0.2.0
```
23. Save the file.
24. Add the file to Git by typing the following command:
```bash
git add _config.yml
```
25. Commit the file to Git by typing the following command:
```bash
git commit -m "add Jekyll configuration"
```
26. Push the file to GitHub by typing the following command:
```bash
git push
```

### Host on a Forge
Etter recommends hosting documentation on a website rather than distributing it as a PDF, because a website is always up to date. GitHub Pages is a free hosting service that works with Jekyll. It automatically builds a static website for you.

27. Go to your repository on GitHub.
28. Click **Settings** in the top menu.
29. Click **Pages** in the left sidebar.
30. Change the None to main under Branch on that page.
31. Click **save**.
32. Refresh the page.
33. Find the URL on that page.



## Further readings

* [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) by Andrew Etter

* [Markdown Guide](https://www.markdownguide.org/)

* [Make a README](https://www.makeareadme.com/)
* [Jekyll](https://jekyllrb.com/)
* [Short Markdown Guide](https://about.gitlab.com/blog/gitlab-markdown-tutorial/)

## FAQ

What is Jekyll?
* Jekyll is a tool that helps you build a static website. You can add a new file called _config.yml to your GitHub repository and set some options in it such as:
```yaml
title: your title
remote_theme: pages-themes/midnight@v0.2.0
```
GitHub Pages has Jekyll in it, so you do not need to install Jekyll on your computer. Once you push this file, GitHub will automatically build your site.

Why do we need version control?
* We need version control because sometimes we have many ideas or we work with other people. After we try one way to code, we want to roll back or try a different approach. Git lets developers work safely. Developers never lose their work with Git.

Why do we use Markdown to write our resume instead of HTML?
* Markdown is easy to write and learn, but HTML requires many tags which makes it harder to read and edit. Some static website generators can help us convert Markdown to HTML.

What if I have problems with Git?
* Git can be hard to understand at first, but there are many tutorials available online, and you can find the Git documentation. The best way to learn is to practice, so do not be afraid to try.

Why use Jekyll instead of other static site generators?

* Jekyll is a popular static site generator that works well with GitHub. It is good for new developers to build their own site. New developers do not need to deal with the environment and the complex operations. Everything in GitHub Pages is pretty simple. You do not need to build the site on your computer.

What if I cannot install Git on my computer?

You can download Git from the official website. Choose the version that matches your operating system. After downloading , follow the instruction they give and use the default settings. If you still have problems, make sure you download the right version, or ask for help on the Stack Overflow website which can be found from Google.

Why is my resume not updating after I changed the Markdown file?
* This is a good question, After you change your Markdown file and push to GitHub, GitHub Pages will build your website automatically. You may need to wait a few minutes. Just make sure you push your file to GitHub correctly.

## Credits

Special thanks to
* Sage Stoddart
* Dat Nguyen

* Theme by mattgraham
