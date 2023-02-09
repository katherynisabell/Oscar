![image](https://user-images.githubusercontent.com/111913185/217900503-df7e31d9-270a-41e2-94bc-f0e60c04ad55.png)

# Story card :clipboard:

__As a__ 
Web Dev :tipping_hand_woman: <br> 
__I want to__
Create a webservice using Git Bash command line and Render :desktop_computer: <br>
__So that__ 
I can have an awesome site :tada: <br>

## Introduction :wave:

The purpose of this README is to document the process of using GitBash as an emulation layer for a Git command line. In this README we will show a user how to download GitBash, utilize the basic functions in GitBash, and push a Git repo to render, and utilize Render to deploy a web service. <br>

## Resources :gear:

https://www.atlassian.com/git/tutorials/git-bash <br>
https://render.com/docs/web-services <br>
https://www.hostinger.com/tutorials/basic-git-commands <br>

## Set Up Dev Space :nerd_face:

- [ ] Download Git bash https://gitforwindows.org/ <br>

- [ ] Download Node.js https://nodejs.dev/en/ <br>

- [ ] Create a new Github repo <br>
![image](https://user-images.githubusercontent.com/111913185/217906381-803b0866-bdc8-4469-aa4e-65b5712abc70.png) <br>


- [ ] After new repo is created grab the link to code <br>
![image](https://user-images.githubusercontent.com/111913185/217906855-6dfba879-f501-485f-8912-32ef4c0c7ea8.png) <br>

- [ ] Open the git bash comand terminal <br>

- [ ] CD into where the file should be cloned (Desktop for tutorial purposed) `cd Desktop` <br>

- [ ] `git clone` Clone repo <br>

## Let's Code :keyboard:

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
## Let's Deploy :rocket:

- [ ] Go to render (create account if needed)<br>
- [ ] Create a new web service, connect to Github repo, change start to be Node.js, add yarn if needed<br>
- [ ] Initialize the web service in Git Bash terminal by calling node app.js <br>

![image](https://user-images.githubusercontent.com/111913185/217900556-9aa3f6d0-7f21-46c3-b641-4955ec13169e.png)
