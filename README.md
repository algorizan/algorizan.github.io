# Hosting Your Resume on GitHub Pages: A Beginner's Guide

## Purpose

These instructions will show you how to host your personal resume or CV on GitHub Pages with a static file website generator.
This guide will also relate each practical step to the general principles of Andrew Etter's book Modern Technical Writing.

## Prerequisites
<!-- This should include a resume formatted in Markdown
- Include a link to a good Markdown tutorial under "More Resources." You do not need to explain how to use Markdown. -->

- **GitHub Account**: If you haven't yet, create a [GitHub account](https://github.com/join).
- **Text Editor**: Use a text editor of your choice.
    - This guide will use [Visual Studio Code](https://code.visualstudio.com/).
- **Resume**: You'll need your resume formatted in Markdown.
    - Learn about [GitHub Flavoured Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github).
- **Git**: have git set up with your text editor.
    - Learn [how to do it on VS Code](https://code.visualstudio.com/docs/sourcecontrol/intro-to-git).


## Instructions
<!--
- Use headings and numbered lists
- Remember to use each step to explain both how to follow the tools and model Etter recommends and how to host a resume in GitHub Pages or Codeberg Pages. It's up to you whether you 1) begin with Etter's general process and then demonstrate the process with a practical step involving your resume, or 2) begin with the practical steps for hosting a resume and relate each practical step to a concept in Etter's book.
- Add an animated gif: Include a demo using an animated gif in your README. The gif should feature your own resume (showing your own name).
-->

### Step 1: Create the Repository
<!-- Etter's concept = Use Distributed Version Control -->

First, we will create a repository for our project on GitHub, which relates to the concept of "using distributed version control" in Etter's book.

1. Log in to [GitHub](https://github.com/login).
2. Create a [new repository](https://github.com/new) in your GitHub account named `username.github.io`, where "username" is your actual GitHub username.
3. Click the "Code" button on your new repository's page and copy the URL from your browser.
3. Create a folder on your computer where you want to store the repository, and give it the same name as the repository.
4. Right-click on the folder and click "Open with Code" to open the folder with VS Code.
5. Click on the "Terminal" button in the top bar on VS Code and select "New Terminal".
6. Type `git clone <repository URL>` (where `<repository URL>` is the URL you copied earlier from your GitHub repository) into the terminal and press Enter.

### Step 2: Create the README and Resume Files
<!-- Etter's concept = Use Lightweight Markup -->

Next, using Andrew Etter's concept of "using Lightweight Markup", we are going to create our README file and resume using GitHub Flavoured Markdown.

1. Create a file called `README.md` in the top level (root) of your directory.
2. Add a title and a short paragraph describing the purpose of your project (i.e., hosting your resume).
3. Save your README file for now, you can add anything else you want later on.
4. Create a new file for your resume, but name it `index.md`. This is so that GitHub knows this is the file you want to host as your website's main page.
5. Add all your resume information to the `index.md` file in GitHub Flavoured Markdown and save it. Don't worry about making it perfect now, you'll be able to edit it as much as you want later.
6. Commit all your files using git or using VS Code's interface as you learned in the VS Code Git tutorial from the Prerequisites section above.
7. Push your changes using the interface, or simply entering `git push` into the terminal.

### Step 3: Enable GitHub Pages

Etter's book emphasizes single-source publishing and static websites, so we are going to host our resume with GitHub Pages.

1. Click on the "Settings" tab on your GitHub repository.
2. Scroll down to the "GitHub Pages" section.
3. Under "Source", select the branch where your README and index files are located (usually "main" or "master").
4. Click the "Save" button.
5. Access your resume page, which should be on your personal user page at `https://username.github.io/`, where `username` is your GitHub username. It might take a few minutes to be accessible.

Here is a video demo of what it looks like to commit your changes in VS Code, push them to GitHub, and opening the hosted resume from your repository.
![screencapture](https://github.com/algorizan/algorizan.github.io/blob/main/assets/img/screencapture.gif)

## More Resources
<!-- Include a Markdown tutorial and at least three other resources. -->
- [Markdown tutorial](https://www.markdowntutorial.com/)
- [GitHub Flavored Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github)
- [Setting up Git with VS Code](https://code.visualstudio.com/docs/sourcecontrol/intro-to-git)
- [Setting up Git on its own](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)
- [Adding a theme to your GitHub Pages site using Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll)


## Authors & Acknowledgments

- **Izan Cuetara Diez** - *Main Author* - [@algorizan](https://github.com/algorizan)
- **Billie Thompson** - *Provided [README Template](https://github.com/PurpleBooth/a-good-readme-template)* - [@PurpleBooth](https://github.com/PurpleBooth)
- **Dean Attali** - *Provided [beautiful-jekyll](https://github.com/daattali/beautiful-jekyll) theme* - [@dattali](https://github.com/daattali)

## FAQs <!-- TODO -->
<!-- Add (and answer) two FAQs, as described below:
- A question about the overall process, such as "Why is Markdown better than a word processor?"
- A question about the practical details, such as "Why is my resume not showing up?"
    - You may use the example FAQs, or come up with your own. -->

