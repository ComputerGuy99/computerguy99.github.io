## Creating a resume using markdown, Github, and Jekyll

### Intended Audience
Are you looking to enhance your resume? Feel like your computer skills are not very advanced? If so you have come to the right place. If you can navigate the internet using a web browser which I am certain you can, otherwise you would not be reading this guide, then you should have no trouble completing the steps that follow. By the end of this guide you will have learned how to write a resume in GitHub flavored markdown, host it using GitHub, and customize it to your liking with the help of a Jekyll theme.

### Prerequisites
If you are able to do basic tasks on a modern computer such as web browsing, and editing documents in word, and you have an email address you should be able to follow this guide.

### Preparation
* #### Creating your GitHub Account
 1. Visit the [GitHub](https://github.com/ "GitHub Homepage") homepage.
 2. Once the page loads create a new account by entering a user name, your existing email address, and a new password.
 3. Click on the large green button labeled _`Sign up for GitHub`_
 4. Login to the email account you used to create your github account.
 5. In your inbox you should see a new message asking you to verify your account. Open it.
 6. Click on the link given in the email message from GitHub.
 7. You will see a webpage with a blue banner at the top notifying you that _`Your email was verified.`_

* #### Installing the Atom Text Editor
 1. Visit the [Atom homepage](https://atom.io/ "Atom Homepage").
 2. In the middle of the page you will see a yellow button labeled `Download` Click on it.
 3. Once the Atom installer has finished downloading onto your computer's hard drive open it.
 4. Follow the on screen installation wizard to install Atom on your computer.

### Writing Your Resume and Hosting it on GitHub
1. Visit [this](https://www.markdowntutorial.com/ "Markdown Tutorial") site and follow the tutorial to learn the basics of markdown. More resources are available below.
2. Once you are comfortable with markdown. Launch the Atom text editor.
3. Once atom has loaded press `ctrl + N` on your keyboard to create a new file.
4. In the new file begin writing your resume in GitHub flavored markdown.
5. You may close the getting started tab and press `ctrl + shift + M` on your keyboard to get a live preview of your markdown code.
6. Press `ctrl + S` to save the file you created in step 3 using the `.md` extension.
7. Once you have finished writing your resume in markdown save it as `“index.md”` by pressing `ctrl + shift + S` on your keyboard or renaming the file that you saved in step 6.
8. Log into your GitHub Account.
9. Create a new repository using the green button labeled `create` in the top right corner of the overview tab.
10.	Select a name for your repository in the format “name.github.io”, where name is the username of your GitHub account.
11. Click on the `create repository` button.
12.	Now that you have created a repository you will be taken to a page that explains how to setup your new repository.
13. Under the “Quick setup” heading you will find the hyperlink “uploading an existing file”. Click on it
14.	A new page will open where you will be asked to choose files for your repository. Click on the “choose your files” hyperlink.
15. Using the upload window that appears, navigate to the path/location where you saved your markdown formatted resume (index.md file) in step 7 and select it.
16.	Once your index.md file has finished uploading scroll down to the bottom of the webpage.
17. Enter a description if desired, and click on the `commit changes` button.
18. Now you should see a page that allows you to configure your repository. Below the two hyperlinks “your-account-name /  reponame.github.io” there will be multiple tabs labeled `Code`, `Issues`, `Pull requests`, etc. Leave this page open in a separate browser tab or save it's URL as you will be referring to it many times.
19. Click on the “Settings” tab and scroll down until you see the heading “**GitHub Pages**”.
20. Click on the dropdown menu below the subheading “**Source**” and select “master branch”. The page will reload.
21. Scroll down again until you see the heading “**GitHub Pages**” once more. The URL to your repository (personal website) is given inside a blue banner under the “**GitHub Pages**” heading that says “Your site is ready to be published at "reponame.github.io”".
22. Click on the link "reponame.github.io” inside the blue banner and your resume should load in a new tab.
23. Scroll through the page and verify that your resume is being rendered correctly
24. If you are unsatisfied with the formatting of your resume go back to the repository configuration page introduced in step 18 and follow the next step. If the formatting and content is to your liking begin "Applying a Jekyll Theme to your Resume".
25. You should now be back at the repository configuration page you visited in step 18.
26. Click on the file called "index.md" and a new page will load with a preview of the markdown formatted resume you uploaded in step 15.
27. Look at the menu bar above the preview of your "index.md" file. It will have a pencil icon in the top right hand corner. Click on it.
28. You may now edit the markdown code of your resume.
29. Once you have finished editing your resume scroll down until you see a green `Commit changes` button.
30. If desired, enter a description of the changes you made in the provided textbox above the `Commit changes` button
31. Click the `Commit changes` button to apply the changes you have made.
32. Reopen the link to your resume that was given to you in step 22. The changes you submitted in the previous step should now appear.

![Resume Template GIF](https://dl.dropboxusercontent.com/s/r1j50hrghxuxpig/resume_template.GIF)

### Applying a Jekyll Theme to your Resume
1. Go back to the repository configuration page that you used in steps 18 and 24 when "Writing Your Resume and Hosting it on GitHub"
2. Click on the “Settings” tab and scroll down until you see the heading “**GitHub Pages**” once more.
3. Click on the 'Change theme' button.
4. You will be presented with a variety of Jekyll templates that are already hosted on GitHub and ready for you to use.
5. While browsing through the themes it is strongly recommended to read the README.md file posted on each theme's repository page in order to ensure that it has additional customization options that you might want now or in the future such as the ability to change the title, description, images, etc.
6. click on the view on github link at the top right of each theme that you are considering to open its repository page.
7. Browse through the various themes and their respective repository pages until you find one that you like. If you do not like any of the themes continue to step 9. Else follow step 8
8. If you find a theme you like click the green `Select theme` button above the preview of the theme and continue to step 11.
9. If you do not like any of the themes you may look for others online or select from the ones posted in "More Resources" below.
10. Once you find a third party theme you do like follow the included readme file to set it up. Setting up a third party theme will either involve uploading all of the files that make up the theme to your github repository. However, if the theme has a github page you may fork it by clicking the grey `fork` button at the top right corner of the theme's github page. This will essentially create a new repository in your account containing a copy of the theme's code which you may then modify to fit your needs. Depending on how the theme is implemented you might not even need a markdown formatted resume.
11. Visit the link to your resume "reponame.github.io”. Your resume should now appear with the new theme you selected.

### Frequently Asked Questions
Q: Why should I use markdown to write my resume instead of a traditional word processor such as Word, Pages, or Google Docs?

A: Markdown is easier to write than HTML (most commonly used to write websites) and can easily be converted to HTML allowing you to make your resume into a webpage.

Q: Why would I want to have my resume in the format of a webpage?

A: Having your resume in the form of a webpage allows you to distribute it more easily since you can host it online and just give employers a URL to the webpage. Having a webpage also ensures compatibility with most devices especially mobile devices which can often display traditional computer files incorrectly depending on the applications installed, the software configuration, and limitations of the platform.

Q: After selecting my template and/or editing files in my repository I clicked on `commit changes` however my webpage is not being updated. Am I doing something wrong?

A: This is completely normal. It can take a few minutes or even up to an hour for committed changes to appear on your webpage as it takes time to update the webpage's code and restart the webserver behind the scenes. Be patient. If there is a problem with your files which prevents the updated webpage from being generated and hosted behind the scenes you will receive a warning email from GitHub.

### More resources
* a quick guide to GitHub flavored markdown is available [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [this](http://jekyllthemes.org/) is a library of additional Jekyll themes.
* tips on writing a resume may be found [here](https://www.linkedin.com/pulse/ats-resumes-fact-fiction-adrienne-tom-cerm-mcrs/)

### Authors and Acknowledgments
* Thanks to GitHub user Steve Smith (orderedlist) for creating the modernist Jekyll theme.
* Thanks to my group members Robert Rose and Lam Nguyen for helping revise this guide
