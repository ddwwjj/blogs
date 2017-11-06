## Getting started with github-upload project

Github is like the Facebook for software engineers. It could be used to well organize knowledges, codes, projects and so on. So let's get started! 

### Step One - Understanding the github flow

Branching is a core concept in Git. It allows us to implement different parts or features of one project more easily. During the developing process, we can feel free to commit changes, go back to old stages and collaborate with others. Github working flow description of how branching works.    

![Github Logo](/github_flow.PNG)
More details see [GitHub flow](https://guides.github.com/introduction/flow/).

### Step Two - Create a repository and upload project

Based on github flow, uploading an existing project is as follows: 

> Create -> Clone -> Copy+Paste -> Add -> commit -> Push


#### 1. Create ####

Create a repository named "homework".

#### 2. Clone ####

Select a directory in local computer and clone the newly created repository to that directory.
> git clone https://github.com/ddwwjj/homework.git

#### 3. Copy+Paste ####

Copy the project ready to upload and paste it to the directory 

#### 4. Add ####

Add the project to the staging area so that Git could start tracking changes made to that project
> git add filename (file)

or
> git add projectname (directory)

#### 5. Commit ####

Commit command is for storing staged changes, it is like a snapshot of the repository.
> git commid -m "first change"

#### 6. Push ####

The push command tells Git where to put commits when it's ready. Push the changes to master branch.
> git push origin master

#Date: 10/26/2017
