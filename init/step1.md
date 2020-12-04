#####  First create a Repository in GitHub and Clone It 

`git clone git@github.com:<username>/katacoda.git`{{copy}}

`cd katacoda`{{copy}}

now go to repo cloned


#####  Install Katacoda CLI to run Katacoda Scenario Build Commands
`
npm install katacoda-cli --global
`{{execute}}

#####  To build/create up Scenarios
`
katacoda scenarios:create
`{{execute}}

##### Fill out the things to configure your Scenarios
```
? Friendly url:  demo
? Scenario Title:  Demo Project
? Scenario Description:  Just a Demo Project 
? Difficulty Level:  Beginner
? Estimated time: (Please specify in minutes or hours e.g. 2 hours) 5
? Number of Steps (Not including intro & finish):  2
? Image:  Bash
? Layout:  Terminal
```
##### To push it back to remote repository

`git add .`{{execute}}

`git commit -m "My first Katacoda scenario"`{{copy}}

`git push`{{execute}}

