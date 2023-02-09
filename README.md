
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

- [ ] Make sure to 'Add a README file' + .gitignore template: node 

![image](https://user-images.githubusercontent.com/111913185/217906381-803b0866-bdc8-4469-aa4e-65b5712abc70.png) <br>

- [ ] After new repo is created grab the link to code <br>

![image](https://user-images.githubusercontent.com/111913185/217906855-6dfba879-f501-485f-8912-32ef4c0c7ea8.png) <br>

- [ ] Open the git bash command terminal <br>

- [ ] CD into where the file should be cloned (Desktop for tutorial purposed) `cd Desktop` <br>

- [ ] Clone repo using the `git clone` command and paste the repo URL we previously copied. Example: `git clone 486favoriteclass/`<br>

- [ ] To make sure all info if up to date in your code use the `git pull` command.

- [ ] Dont forget to install that node.js we downloaded `npm i express` followed by `npm init -y`.

- [ ] lets open up our files!!! `code .`


## Let's Code :keyboard:

- [ ] `touch app.js` and `node app.js` will add some files. Dont freak, we will use those! This is where web page content will go 

```diff

- [ ] Need to put node express thing into app.js and a small code snippet into index.html
- to display like “I DEPLOYED A WEBPAGE” (show user code snippet)<br>

- Show and explain basic commands such as 
- `touch` (adds a file), **add one more**<br> 
->NOTE FROM NICOLE: do you want to add instructions on the code we did for mike? like what we put in our app.js file?
``` 

- [ ] You're ready to send it all back to GitHub?? Cool. Lets see what files you altered by `git status`

- [ ] Notice some files that are red? Lets fix that `git add.`

- [ ] Check yourself by `git status` again. Notice they are green!!! 

- [ ] Lets leave ourselves a note telling us what we did by `git commit -m "note here!"` 

- [ ] and to finish it off, `git push`. you will most likely be asked to sign in. please do so & watch the magic happen !

## Let's Deploy :rocket:

- [ ] Go to render https://render.com/ (sign in with Github)<br>
![image](https://user-images.githubusercontent.com/111913185/217911417-a5f5f807-9df5-42c4-937d-199158216d9b.png) <br>

```diff
- [ ] Create a new web service, connect to Github repo, change start to be Node.js, add yarn if needed<br>

- [ ] Initialize the web service in Git Bash terminal by calling node app.js <br>
```

![image](https://user-images.githubusercontent.com/111913185/217900556-9aa3f6d0-7f21-46c3-b641-4955ec13169e.png)
