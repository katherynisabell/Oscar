![image](https://user-images.githubusercontent.com/111913185/217900503-df7e31d9-270a-41e2-94bc-f0e60c04ad55.png)

# Story card  <br>

__As a web dev__ <br>
__I want to create a webservice using Git Bash command line and Render__<br>
__So that I can have an awesome site__ <br>

# Introduction

The purpose of this README is to document the process of using GitBash as an emulation layer for a Git command line. In this README we will show a user how to download GitBash, utilize the basic functions in GitBash, and push a Git repo to render, and utilize Render to deploy a web service. <br>

# Resources

https://www.atlassian.com/git/tutorials/git-bash <br>
https://render.com/docs/web-services <br>
https://www.hostinger.com/tutorials/basic-git-commands <br>

# Setting up your dev space

- [ ] Download Git bash https://gitforwindows.org/ <br>

- [ ] Download Node.js https://nodejs.dev/en/ <br>

- [ ] Create a new Github repo <br>

- [ ] After new repo is created grab the link to code <br>

- [ ] Open the git bash terminal (either in VS code or the app)<br>

- [ ] CD to where the file should be cloned (Desktop) (show code snippet)<br>

- [ ] `git clone` Clone repo <br>

# Setting up your code

- [ ] Go to files and open the cloned repo + CD into cloned repo <br>
- [ ] Use `touch add app.js` where the node stuff will go and `touch index.html` where web page content will go (show user code snippet)<br>
- [ ] Need to put node express thing into app.js and a small code snippet into index.html to display like “I DEPLOYED A WEBPAGE” (show user code snippet)<br>
Show and explain basic commands such as 
`git pull` (gets most recent files from repo), 
`touch` (adds a file), **add one more**<br>
Step 11-14: Explain you can modify your code then push it to the repo using these commands (
```git add
git commit -m
git push
git status
```
# Setting up Render to deploy your webpage

- [ ] Go to render (create account if needed)<br>
- [ ] Create a new web service, connect to Github repo, change start to be Node.js, add yarn if needed<br>
- [ ] Initialize the web service in Git Bash terminal by calling node app.js <br>

![image](https://user-images.githubusercontent.com/111913185/217900556-9aa3f6d0-7f21-46c3-b641-4955ec13169e.png)
