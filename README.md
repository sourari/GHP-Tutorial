## Crash course on creating project websites with GitHub Pages

Creating websites for your projects is easy with GitHub Pages. This site is an example - a simple GitHub pages website, hosted through github.io with basic Markdown formatting, and using a simple Jekyll theme (Caymen) provided by GitHub. The video below offers a quick introduction to this service.

[![Intro do GH-Pages video](https://img.youtube.com/vi/2MsN8gpT6jY/0.jpg)](https://www.youtube.com/watch?v=2MsN8gpT6jY)

### Creating a project wesite with GitHub Pages
To create a GitHub pages site for a particular project, you:
1. login to your GitHub account and create a new repository, or go to an existing one.
2. click on the Settings tab on the upper right of the project page
3. scroll down to the GitHub Pages section. Press Choose a theme to select a Jekyll theme, or simply select the Master branch as the source if you'd like to build your site from scratch.
4. Now you can use the online editor to add to maintain and preview the content for your website in Markdown files, or make changes locally and push them to your project repo via git.
#### JUST REMEMBER TO COMMIT YOUR CHANGES WHEN YOU'RE DONE!

Whenever I commit to this repository, whether on my local machine or by editing files directly on GitHub, GitHub Pages will automatically run [Jekyll](https://jekyllrb.com/) to rebuild the pages in the site, from the content in the associated Markdown files.

## This page, README.md, is the index for this site. 
But it doesn't need to be the only page. You can create new pages for your site in GitHub or locally with git, and then add them to your index to build a more complete website. (Note that I could also have used html for this site, if I had named this page **index.html**.)

For example, here's a link to another page in this repo, which includes additional resources for learning Markdown: 
[Markdown](/markdown.md)

### Find more info about [GitHub Pages here](https://pages.github.com/)

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/kevenson/GHP-Testing/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out more [documentation](https://help.github.com/categories/github-pages-basics/).
